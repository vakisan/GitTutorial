# GitTutorial
How to use GitHub/Git practice (First Time Using Git/GitHub)

Followed tutorial on Youtube
https://www.youtube.com/watch?v=xuB1Id2Wxak

Written By Vakisan Manoharan - 1st Year Computer Science Student

Step 1 :
Create a folder to store the Git repository files.

Step 2:
Open Terminal in MacOS at the folder location.
Use "pwd" command to print working directory ie. current directory.
Use "ls" command to view all the folders in the current directory.
Use "cd" command to change change directory.
If folder has spaces in it type the first few of its characters followed by Tab key.

Step 3:
We need to create a local repository to push and pull from the central server repository.
Run the following line in bash--> git init.
Terminal displays having created git repository.

Step 4:
We need the location of the central server repository for the project.
We add a new repository on GitHub.com.
Click on the clone or download green button; a popup will appear with the link of the repository.
Alternatively you can copy the url of the repository from the browser address bar <--NOTE must add .git extension at end.

Step 5:
Run the following line in bash--> git remote add origin "url".

Step 6:
Run the following line in bash--> git pull origin master
The repository files should now appear in the directory you created.

Step 7:
Step 1 to 6 can be skipped if using the command git clone "url" if you already have a repository on GitHub.

Run following line in bash to get status of all the files which are added to index and ready to commit--> git status ;
Run following line in bash to add files to the index--> git add ;
Run following line in bash to commit changes--> git commit ;
