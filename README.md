ls - Shows everything under the current section we are on
cd - Change to another directory
cd .. - Go up one directory
mkdir - Creates a new folder
touch - Creates a new file introduction
rm - Removes a folder or file 


Git commands
// Initializes the local directory as a repository
1) git init 

// Start tracking files
2) git add ¨NameofFile.txt¨

// Save Point (commit)
3) git commit -m ¨Adding README with some commands¨

// Link the repositories together
4) git remote add origin url-to-github-here

// Uploads every change to github 
5) git push -origin master
   git push -origin main

// To save a new change we need to run steps 2, 3, and 5 

// Show the current file tracking status 
git status

rm -rf .git
