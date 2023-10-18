# Init a repository

Changed default master name on github to main
$ git branch -m master main # now change it on local
$ git fetch origin # gets new remote branch name
$ git branch -u origin/main main # upstream is origin/main
$ git remote prune origin # removes previous ref 
