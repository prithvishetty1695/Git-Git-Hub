mnt before adding repositary
cd command used to navigate between direcoty and files
ls command finding the list in directory/folders
git init command is used to setup .git files for  complete record of workings.
git add adding files in the repositary
git status to find the status
git add .  -> adds all unstage files
git commit -> is used to snapshot & modifications you've done stores them in a tree
git --help
git rm -rf command used to force remove 

git commit -m "Message"
git commit -a -m "message" for all tracked files
git log list of all commits
git checkout  - go back to original commit
git revert - back in time to 1 commit 
git reset --hard (dangerouos) soft, hard 
mutiple commits 
git reset --soft     

git log --oneline (shortens commit id)

git branches:  create spearate development paths without overrriding progress
release/master
development branch

to add file command : touch filename.format

to create branch git checkout -b filename 
creates and switches to the branch

to go back to master branh = git checkout master
 merging braches to master : git merge branchhname 
merging manages complexity exponential better than any other version control software
Delete : git branch -d nameofbranch
List of branches : git branch -a


git remote add origin link

git remote v :  to check

fetch(pull)   : git pull origin master

git push -u origin master

git push origin --delete branchname


To get more information click on the below link
https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html
