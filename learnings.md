# 5 Things I have learned about Git and GitHub
1. Clone — used to create a copy of an existing Git repository.
```github
$ git clone <repository name>
```
2. Add — add changed files to the staging area and that can be saved in the git repository via committing.
- adding a specific changed file to the staging —
```github
$ git add <file-name>
```
- add all the changed files to the staging —
```github
$ git add .
```
3. Status — show the status of the working tree(staged or unstaged files) such as which files have recently been modified.
```github
$ git status
```
4. Commit — save your changes to the local Git repository.
```github
$ git commit -m “commit message eg- initial commit”
```
5. Push — uploading local changes to a specific remote branch.
```github
$ git push origin <remote branch name>
```

# 2 Have More of my learnings
6. Pull — to download and integrate remote branch changes in your local branch.
```githup
$ git pull origin <remote branch name>
```
7. Branch — create a new pointer head on the commits.
```github
$ git branch <branch-name>
```

