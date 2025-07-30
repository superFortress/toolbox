# cheatsheet

Commands for use with git.

## Setup

| Command                       | Description                   |
| ----------------------------- | ----------------------------- |
| `git init`                    | initialize new git repository |
| `git clone "url"`             | clone github repository       |
| `git remote add origin "url"` | link to github repository     |

## Push

| Command                   | Description                 |
| ------------------------- | --------------------------- |
| `git add .`               | prepare all changes         |
| `git commit -m "message"` | commit changes with message |
| `git push`                | push changes to github      |

## Pull

| Command    | Description              |
| ---------- | ------------------------ |
| `git pull` | pull changes from github |

## Branch

| Command                              | Description                |
| ------------------------------------ | -------------------------- |
| `git branch "main"`                  | clone current branch       |
| `git checkout --track "origin/main"` | switch to and track branch |
| `git branch -d "main"`               | delete branch              |
| `git branch -m "main"`               | rename current branch      |
| `git merge "main"`                   | merge with current branch  |

## Config

| Command                                         | Description                 |
| ----------------------------------------------- | --------------------------- |
| `git config --global core.editor "nano"`        | use nano editor             |
| `git config --global core.editor "vim"`         | use vim editor              |
| `git config pull.rebase false`                  | avoid merge pull prompts    |
| `git config --global init.defaultBranch "main"` | default new repos to "main" |

## Fixes

| Command                                            | Description                  |
| -------------------------------------------------- | ---------------------------- |
| `git pull origin main --allow-unrelated-histories` | merge unrelated histories    |
| `git push --force`                                 | overwrite remote branch      |
| `git remote set-url origin "url"`                  | change github repository url |

## Info

| Command             | Description          |
| ------------------- | -------------------- |
| `git status`        | see current changes  |
| `git log --oneline` | short commit history |
