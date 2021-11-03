---
id: git-cheatsheet
title: Git cheatsheet
description: Useful git commands
slug: /git-cheatsheet
---

## Branches

### Switch to new branch

Creates a new branch and adds any currently unstaged files.

`git switch -c <new-branch>`

### Delete branch

`git branch -d <branch-name>` (local branch)  
`git push origin --delete <branch-name>` (remote branch)
