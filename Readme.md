# git basic commands 
1 . To check git version -> | git --v | git -version 
2 . To initialize .git folder we need to use -> | git init 
3 . To verify what is the git remote repo use -> | git remote -v 
4 . To add remote to local repo use -> | git remote add origin git-remote-repo-url
5 . To check current branch status use -> | git status
6 . To check git commit history use -> | git log
7 . To get file tracked by git or to make files to staging area use -> | git add file1 file2 | git add . 
8 . To commit,is having set of changes till the point & have all changed content(repo) | git commit -m "commit message"
9 . To undo changes in the unstaged changes use -> | git stash
10 . To apply changes to staging to undo git stash -> | git stash pop
11 . To undo to the previous n commit/s use -> | git reset HEAD~n 
12 . To discard commit process use -> | rm -Force .git/index.lock 
13 . To create a branch use -> | git branch branch-name | git checkout -b branch-name
14 . To relocate to a particular branch use -> | git checkout branch-name 
15 . To merge changes from a branch use -> | git merge branch-name
16 . To delete safely a branch use -> | git brnach -d  branch-name 
17 . To foreful delete a branch use -> | git branch -D branch-name
18 . To clone to a particular repo use -> | git clone remote-git-reop-url 
19 . To push changes to a remote reop -> | git push -u origin main  - (first time) | git push 
20 . To check difference between current commit and changes after it -> | git diff 
 


