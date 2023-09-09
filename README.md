# Git_Guideline
This repository contains the guideline for using GitHub


1. Check out the branch
- To check out to another branch
`git checkout branch_name`

- To create a new branch from the current branch
`git checkout -b new_branch_name`

2. Pull
- To pull all commit on master branch to local branch
`git pull`

3. Push
- To push new commit to master branch
`git push`

- Force push when using some action (e.g. rebase)
`git push -f` or `git push --force`

4. Add
- To add all code changes before committing
`git add file_name`

5. Commit
- Commit with message before pushing
`git commit -m "message"`

6. Status
- See the all changes status of current directory
`git status`

6. Diff
- Show all the difference after changing
`git diff` or `git diff specific_file`

7. Rebase 
`git rebase -i main`
