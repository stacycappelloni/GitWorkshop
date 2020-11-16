# Git Workshop 11-16-2020  

## Walkthrough

1.Fork this repository 
  * click on the fork button on the top right
  * select the desired location that you would like it forked
  
2. Clone the new forked repository
  * click the download button in the top right
  * copy the repo https
  * in the terminal, in the directory that you would like the project type git clone <repo https>
  * git status
  
3. Make a branch of the repository
  * in the GitWorkshop directory type git branch <yourname>branch
  * to go to that branch type git checkout <yourname>branch
  * edit the file called names.txt by adding your name
  * make sure to add and commit your changes on the branch
  * to go back to the master branch type git checkout master
  * to merge your branch back to master type git merge <yourname>branch
  * git status
 
4. Create a file to ignore
  * create a file called ignoreme.txt
  * git status
  
5. Creating a .gitignore 
  * using your favorite text editor create a file called .gitignore
  * add the extensions or names of files you do not want included - ignoreme.txt
  * save the file and add, commit, and push
  * what happens to useless.txt?
  * git status
