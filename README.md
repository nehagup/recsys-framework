# recsys-framework

Install Anaconda for Python 3.6 for your operating system from https://www.anaconda.com/download/

Create an Environment. Open Anaconda Navigator, select “Environments,” and create a new “RecSys” environment for Python 3.6 or newer.

Install SurpriseLib
From the RecSys environment you just made, click the arrow next to it and select “Open Terminal.” In the terminal, run:

conda install -c conda-forge scikit-surprise

Hit ‘y’ to proceed if prompted.

Get the Course Materials at http://media.sundog-soft.com/RecSys/RecSys-Materials.zip and unzip them. 
Get the MovieLens Dataset at http://media.sundog-soft.com/RecSys/ml-latest-small.zip – unzip it, and place the resulting ml-latest-small folder inside your course materials folder.

Make some movie recommendations!

From Anaconda Navigator, make sure the RecSys environment is still selected, and click on Home.
Under spyder, hit the install button, and when it’s done, hit the launch button. Click “Allow access” if prompted.
Open the GettingStarted/GettingStarted.py file from your course materials.
Click on the green “play” button to run the script, and you’ll see a summary of the movie ratings from a specific user – and our automatic recommendations for other movies he should see!
