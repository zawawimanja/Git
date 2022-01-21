# LearnGit

- Local repo is in the pc
- Remote repo is in github
                     

# Init

- git init
- git add .
- git commit -m "a"
- git push origin master
- git remote add origin <server>


## Branch

- git checkout -b branch
- git add .
- git commit -m  "branch"
- git push origin branch

## Contribute SomeoneProject

- git clone (kena fork dulu project pastu copy link url )
- git status
- git add .
- git commit -m"commit"
- git push origin master
- go to our fork project in github & create pull request
- then owner of the project will merge if it ok
  
  ## Merge branch no1 into main
  
- git checkout no1	//create new branch name newbranch
- git checkout master				//going to branch master
- git merge no1				//current branch is master, it will merge master file to no1

## Delete branch

- git checkout master
- git branch -d branch

## Misc
- git pull //go to master branch
- git merge
- git status

#DeleteLocalRepoGit
- rm -rf .git




