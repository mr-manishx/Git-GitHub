## Git Hidden Folder

There is a hidden folder called `.git` which tells you that our project is a git repo 

if we want to create a git repo in a new project we create the folder and the initialize that repo using `git init`

```
mkdir /workspace/temp/new-project
cd /workspace/temp/new-project
git init
touch Readme.md
code Readme.md
git add Readme.md
git status
# makes change to readme.md
git commit -a -m "add readme file"
```

## Cloning

We can clone three ways: HTTPS, SSH, Github CLI

Since we are using GitHub Codespaces we'll create a temporary directory in our workspace

```sh
mkdir /workspace/temp
cd /workspace/temp
```

### HTTPS

```sh
git clone https://github.com/mr-manishx/Git-GitHub.git
cd GitHub-Example
```

## commits 


## Add

When we want to stage changes that will be included in the commit we can use the . to add all posible files.

```
git add Readme.md
git add .
```

## Reset
Reset allows you to move Staged changes to be unstaged.
This  is useful when you to revert all files not to be not commited

```
git add .
git reset
```

> git reset will revert a git add .


## Status

Git status shows you what files will or will not be commited.

```
git status
```