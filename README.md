# example-repo
Cloning repo, editing, and using with git.

NEVER CLONE A REPO INTO A REPO

 - git clone repo-url

  - modify / edit a file = MAKE SURE YOU SAVE
  - git add -A = adds from working area to staging area
  - git commit -m "message" = adds from staging area to local repo
  - git push origin main = pushes local repo to remote repo

  - git status = check mismatches between work, staging, local, origin


---


# Branching

Viewing Branches
 - git branch -a = see all branches

Creating Branch
 - git checkout -b [name] = add new branch and moved us onto it

Move onto Branch
 - git checkout [name] = moves us onto existing branch

Pushing Branch to Main
 - git push origin [name] = pushes branch to main
 - origin > remote > github
 - [name] > branch with changes we want to add
