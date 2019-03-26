# gitbasics

# Git global config

git config --global user.name 'srontala'

git config --global user.email 'surender.rontala@gmail.com'

# Intialize local repository

git init

# git add - Add files to Index

git add <files>
git add *
git add *.html

# git status - check Status of Working Tree

git status

# git commit - commit changes to Index

git commit -m 'Intial commit'

# git push - Push to Remote Repository

git push

# git pull - Pull Latest changes From Repository

git pull

#git clone - Clone Repository Into A New Directory

git clone

# git rm --cached - Remove file from statging

git rm --cached <filename>

# git ignore - 

touch .gitignore

# git branch - to create branch

git branch sprint1

# git checkout - To Switch Branch

git checkout sprint1

# git merge - Merge branch to master

git checkout master (switch to master and then merge branch)
git merge sprint1 -m 'merged sprint1 branch to master'

# git branch -a : To check branches

git branch -a

# To add Remote Repository

git remote add origin https://github.com/rsurenderreddy/gitbasics.git
git push -u origin master