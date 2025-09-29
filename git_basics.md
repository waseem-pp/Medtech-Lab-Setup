## Git Basics

### git init
This command is used to **initialize a new Git repository** in the current directory. It creates a hidden '.git' folder that tracks changes to your files, essentially starting version control for your project.

### git add
This command **stages files** for the next commit. It doesn't permanently save the changes yet, but it tells Git which specific modifications or new files you want to include in the snapshot you want to create.

### git commit
This command takes all the changes you've staged with 'git add' and **permanently records them** as a new snapshot in the project history. You've must always include a descriptive message with the commit to explain what changes were made.

### git push
This command is used to **upload your local commits** to a remote repository, such as one hosted on GitHub. It synchronizes your version of the project history with the remote server, making your changes available to others.
