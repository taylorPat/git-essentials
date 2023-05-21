# Git commands

## Configure email and pw to indentify yourself with Git
```
git config --global user.name "your name"
git config --global user.email "your@mail.com"
```

## Essentials
```console
# Initialize a git repo to track changes inside a folder (repository)
git init

# Get status
git status

# add untracked files to staging area 
git add <file>

# and then commit them, to have a clean working tree
git commit -m "test: this is a test commit"

# list commits
git log

# Go back to specific point 
git checkout <git-hash>

# list branches
git branch

# new branch
git branch <branch-name>

# switch to new branch
git checkout <branch-name>

# merge <branch-name> into current branch
git merge <branch-name>
```


