# GitHub

__Fork__  
Creates a git repository on GitHub that has a connection to the original repo. Without a fork, you won’t be able to submit pull requests back to the orginal repo.

__Pull Request__  
Push commits to your forked repo, then on your forked repo go to pull requests, then click ‘Create Pull Request’


# Git 

| Command      | Description |
| :---         | :---           |
| `git status` | Check which files are staged, unstaged, or untracked. |
| `git add <file name / directory>` | Adds a file or directory to the stage (aka index) |
| `git commit [-m ‘what your message is’]` | Writes the staged files to the local git repo |
| `git remote add <name> <url>`  | Add a remote to the current git repo (we usually denote them as origin / upstream) |
| `git remote -v`  | See the names of the repos and what links their connected to |
| `git remote remove <name>` | Remove a remote | 
| `git clone <repo url>` | Copy a repo from GitHub down to your local machine |
| `git push <name of remote> [name of branch]` | Push the branch along with necessary commits to the remote. |
| `git pull <name of remote>` | Fetch the commits at a repo and automatically merges them into your local repo |
