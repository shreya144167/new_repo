stash is cool.
git add .
git status
#----- I don't want to commit them now ---------- 
#------I can temporarily save on git stash---------
#------git commit -m "Git Stash"
git stash -u 
#-------work on another file --------------
git add .
git status
git commit -m "commiting another changes"
git stash --list
git stash show
git stash apply
#--------all saved changes will be listed---
git add .
git status
git commit -m "git stash"
