Git Commands and Syntax

# Initialize & Configure
1) git init
	Initialize a new Git repository.
2) git config --global user.name "Your Name"
	Set the username globally.
3) git config --global user.email "your.email@example.com"
	Set the email globally.

# Basic Operations
1) git status
	Show the working directory status.
2) git add <file>
	Add specific files to the staging area.
3) git add .
	Add all changes in the current directory to the staging area.
4) git commit -m "commit message"
	Commit changes with a message.
5) git log
	View commit history.
6) git diff
	Show changes between commits, branches, etc.

# Branching & Merging
1) git branch
	List branches.
2) git branch <branch-name>
	Create a new branch.
3) git checkout <branch-name>
	Switch to a different branch.
4) git checkout -b <branch-name>
	Create and switch to a new branch.
5) git merge <branch-name>
	Merge a branch into the current branch.
6) git branch -d <branch-name>
	Delete a branch.
7) git log --oneline --graph --all
	Visualize the commit history graphically.

# Remote Repositories
1) git remote add origin <url>
	Connect the local repository to a remote server.
2) git push origin <branch-name>
	Push changes to the remote repository.
3) git pull origin <branch-name>
	Pull changes from the remote repository.
4) git clone <url>
	Clone a remote repository to the local machine.

# File Management
1) git rm <file>
	Remove a file from the repository.
2) git mv <old-name> <new-name>
	Rename or move a file.
3) git diff <file>
	Show changes made to a specific file.
4) git stash
	Stash changes temporarily.
5) git stash apply
	Re-apply the stashed changes.

# Undoing Changes
1) git checkout -- <file>
	Discard changes to a specific file.
2) git reset HEAD <file>
	Unstage a file.
3) git reset --soft HEAD~1
	Undo the last commit, keeping changes staged.
4) git reset --hard HEAD~1
	Undo the last commit, discarding all changes.
5) git revert <commit-id>
	Create a new commit to undo a specific commit.

# Advanced Commands
1) git rebase <branch-name>
	Rebase the current branch onto another branch.
2) git cherry-pick <commit-id>
	Apply a commit from another branch.
3) git apply <patch-file>
	Apply a patch to the repository.
4) git merge --abort
	Abort a merge in progress.
5) git rebase --abort
	Abort a rebase in progress.
