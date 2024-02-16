# Инструкция по работе с Git

# Lesson 1

git add - добавить версионность
## Как представиться в Git 
* git config --global user.name "OwnName"
* git config --global user.email "YourEmail"
## What is Git?
Git is control version of reprository and a DevOps tool used for source code management.It is enabling multiple users.
## Commands in Git 
1. git init - initialization of reprository
2. git status - getting info from Git about current condition
3. git add - adding file to next commits
4. git commit -m "message" - creating commits
5. git log - displaying all commits on screen with hashing
6. git checkout - transition to other commits
7. git checkout master - transition to actual condition to continue work
git diff - to see difference between all commits which commited
## Syntax Markdown
 1. '#' - this hash highlights Title
 2. ===================
 3. **bold style** or __bold style__
 4. *italics style* or _italics style_
 5. ***bold style italics***
 6. ~~Struck-out text~~
 7. * unnumbering lists
 8. 1,2,3 numbering list

# Lesson 2 
## About remote repositories

GitHub's collaborative approach to development depends on publishing commits from your local repository to GitHub for other people to view, fetch, and update.

## Creating remote repositories
You can use the git remote add command to match a remote URL with a name. For example, you'd type the following in the command line:

git remote add origin <REMOTE_URL>

## Cloning with HTTPS URLs

The https:// clone URLs are available on all repositories, regardless of visibility. https:// clone URLs work even if you are behind a firewall or proxy.

## Push operation
git branch -M master
git push -u origin master

## Pull operation
fork - this function provides save project in your repository
