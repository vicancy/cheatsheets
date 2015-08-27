Create
------

Show
-----
Description | Command
----|---
Changes between `<id1>` and `<id2>` | `git diff <id1> <id2>`
History of changes for `<file>` with diffs | `git log -p <file>`
Who changed a `<file>` | `git blame <file>`

Branch
-----
Description | Command
---|---
Delete *local* `<branch>` | `git branch -D <branch>`
Delete *remote* `<branch>` | `git push origin :<branch>`
Clean stale remote branches | `git remote prune origin`

Tag
---
Description | Command
---|---
Create a `<tag>` | `git tag -a <tag> -m "<comments>"`
Push a `<tag>` | `git push origin <tag>`

Config
------
Description | Command
---|---
Save credential | `git config --global credential.helper store`
Get remote url | `git config --get remote.origin.url` or `git remote show origin`
Change remote `<url>` | `git remote set-url origin <url>`
List all the alias | `git config --get-regexp alias`
Set alias and useful alias | `git config --global alias.last log -1 HEAD`, `git config --global alias.unstage reset HEAD --`, `git config --global alias.undo checkout --`
