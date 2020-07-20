# GIT_CONFIGURATION
-git config --global user.name "sunny812546"
-git config --global user.email sun812546@gmail.com
-git config --list
# GIT-GITHUB Simple clone and commit
-git clone SSH (Pull down code from github)
-git status (All Status of your actions)
-git add . (you can see untracked & modified files)
-git status
-git commit -m "Added files" -m "Some Description"
-git push origin master (reflected chanegs in your actual repo)

# add new repo locally
-git init (initialized git repo)
-git status
-git add .
-git status
-git commit -m "" -m ""
-git remote add origin SSH
-git push -u origin master

# git branch
-git branch(list out all branches)
-git checkout -b feature (switch into new branch)
-git diff feature
-git merge feature
-git push -u origin feature
-git pull origin master (from github to your local machine)
-git branch -d feature (delete)

# go back into your commited steps again
-git reset HEAD~1
-git log
-git diff 
-git reset HASHCODE OF YOUR COMMIT
-git reset --hard HASHCODE

