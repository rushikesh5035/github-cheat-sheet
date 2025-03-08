# Git Commands Cheat Sheet 🚀

## **Configuration**

| Command                                                   | Description                              |
| --------------------------------------------------------- | ---------------------------------------- |
| `git config --global user.name "Your Name"`               | Sets the username for Git globally.      |
| `git config --global user.email "your.email@example.com"` | Sets the email address for Git globally. |
| `git config --list`                                       | Displays the current configuration.      |

## **Initialization**

| Command                      | Description                                                   |
| ---------------------------- | ------------------------------------------------------------- |
| `git init`                   | 🏁 Initializes a new Git repository in the current directory. |
| `git clone <repository URL>` | 📥 Clones a remote repository to your local machine.          |

## **Branching and Merging**

| Command                       | Description                                                      |
| ----------------------------- | ---------------------------------------------------------------- |
| `git branch`                  | 🌿 Lists all branches in the repository.                         |
| `git branch <branch-name>`    | 🌱 Creates a new branch.                                         |
| `git checkout <branch-name>`  | 🔄 Switches to the specified branch.                             |
| `git switch <branch-name>`    | 🔄 Also switches branches (newer alternative to `git checkout`). |
| `git merge <branch-name>`     | 🔗 Merges the specified branch into the current branch.          |
| `git branch -d <branch-name>` | 🗑️ Deletes a branch (locally).                                   |

## **Working with Changes**

| Command                  | Description                                                             |
| ------------------------ | ----------------------------------------------------------------------- |
| `git status`             | 📋 Displays the state of the working directory and staging area.        |
| `git add <file>`         | ➕ Stages a specific file for commit.                                   |
| `git add .`              | ➕ Stages all changes in the current directory.                         |
| `git reset <file>`       | 🔄 Unstages a file from the staging area.                               |
| `git reset --hard`       | 🚨 Resets the working directory to the last commit, discarding changes. |
| `git diff`               | 🔍 Shows changes between the working directory and the staging area.    |
| `git diff <branch-name>` | 🔍 Compares changes between the current branch and another branch.      |

## **Committing**

| Command                          | Description                                             |
| -------------------------------- | ------------------------------------------------------- |
| `git commit -m "Commit message"` | 📝 Commits the staged changes with a message.           |
| `git commit --amend`             | 📝 Edits the last commit message or adds changes to it. |

## **Remote Repositories**

| Command                         | Description                                                         |
| ------------------------------- | ------------------------------------------------------------------- |
| `git remote add origin <URL>`   | 🌐 Links a remote repository to the local one.                      |
| `git remote -v`                 | 🌐 Lists remote repositories linked to the local one.               |
| `git push origin <branch-name>` | 📤 Pushes changes to the specified branch on the remote repository. |
| `git pull origin <branch-name>` | 📥 Pulls changes from the remote repository to the local one.       |
| `git fetch`                     | 📥 Fetches changes from the remote without merging them.            |

## **Tagging**

| Command                              | Description                                 |
| ------------------------------------ | ------------------------------------------- |
| `git tag`                            | 🏷️ Lists all tags in the repository.        |
| `git tag <tag-name>`                 | 🏷️ Creates a new tag.                       |
| `git tag -a <tag-name> -m "Message"` | 🏷️ Creates an annotated tag with a message. |
| `git push origin <tag-name>`         | 📤 Pushes the tag to the remote repository. |

## **Stashing**

| Command           | Description                                                           |
| ----------------- | --------------------------------------------------------------------- |
| `git stash`       | 📦 Saves uncommitted changes for later.                               |
| `git stash list`  | 📋 Lists all stashed changes.                                         |
| `git stash apply` | 🔄 Applies stashed changes without removing them from the stash list. |
| `git stash drop`  | 🗑️ Removes a specific stash.                                          |

## **Logs and History**

| Command                  | Description                                    |
| ------------------------ | ---------------------------------------------- |
| `git log`                | 📜 Shows the commit history.                   |
| `git log --oneline`      | 📜 Shows a simplified one-line commit history. |
| `git log --graph`        | 🌳 Displays commits in a tree-like structure.  |
| `git show <commit-hash>` | 🔍 Shows the details of a specific commit.     |

## **Undoing Changes**

| Command                    | Description                                                       |
| -------------------------- | ----------------------------------------------------------------- |
| `git revert <commit-hash>` | 🔙 Creates a new commit to undo the changes of a specific commit. |
| `git reset <commit-hash>`  | 🚨 Resets the repository to a specific commit.                    |

## **Advanced Commands**

| Command                         | Description                                                         |
| ------------------------------- | ------------------------------------------------------------------- |
| `git rebase <branch-name>`      | 🛠️ Reapplies commits from the current branch onto another branch.   |
| `git cherry-pick <commit-hash>` | 🍒 Applies changes from a specific commit to the current branch.    |
| `git bisect`                    | 🔍 Helps find the commit that introduced a bug using binary search. |

## **Deleting Files**

| Command                  | Description                                                                  |
| ------------------------ | ---------------------------------------------------------------------------- |
| `git rm <file>`          | 🗑️ Removes a file from the working directory and stages the removal.         |
| `git rm --cached <file>` | 🗑️ Removes a file from the repository but keeps it in the working directory. |

## **Collaboration**

| Command                                        | Description                                                                   |
| ---------------------------------------------- | ----------------------------------------------------------------------------- |
| `git push --set-upstream origin <branch-name>` | 🔗 Sets the default upstream branch for future pushes.                        |
| `git push -f`                                  | ⚠️ Forces a push, overwriting changes on the remote branch.                   |
| `git pull --rebase`                            | 🔄 Pulls changes and rebases the current branch on top of the remote changes. |
