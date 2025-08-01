<<<<<<< HEAD
# autogen




GIT INTIALIZATION :
-------------------

STEP 1: Go to your project folder  
cd C:\Users\autogen_august1  
:: Navigates to your local project directory  

STEP 2: Initialize Git  
git init  
:: Initializes an empty Git repository in the current folder  

STEP 3: Link your GitHub repository  
git remote add origin https://github.com/pavan-ssp/autogen.git  
:: Adds your GitHub repository as a remote named 'origin'  

STEP 4 (Optional Fix): If remote already exists  
git remote remove origin  
git remote add origin https://github.com/pavan-ssp/autogen.git  
:: Removes existing remote and re-adds it  

STEP 5: Verify the remote URL  
git remote -v  
:: Shows the remote URL and helps confirm it's linked to GitHub  

STEP 6: Stage all project files  
git add .  
:: Adds all files to the staging area for the next commit  

STEP 7: Commit your changes  
git commit -m "Initial commit"  
:: Creates a commit with a message describing the change  

STEP 8: Check your current branch name  
git branch  
:: Displays the current active branch (default could be 'main' or 'master')  

STEP 9: Push to GitHub  
:: If your branch is 'main':  
git push -u origin main  

:: If your branch is 'master':  
git push -u origin master  

:: Pushes your local code to GitHub and links it to the remote branch  
=======
# autogen
>>>>>>> dac2c620f3c587596d07b34314d1dac07cb5e8ab
