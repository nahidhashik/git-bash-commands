   ![This is an image](https://www.google.com/imgres?imgurl=https%3A%2F%2Fi.pinimg.com%2Foriginals%2F52%2Fea%2Fbe%2F52eabecf424b217807d0e557b9a0c38e.jpg&imgrefurl=https%3A%2F%2Fwww.pinterest.com%2Fpin%2F308637380694972107%2F&tbnid=XYqIFbgQij7msM&vet=12ahUKEwj2rcjn7bT8AhV_KbcAHccfD8oQMygDegUIARDGAQ..i&docid=AlCx-WPWgz1SQM&w=896&h=896&q=github%20logo&hl=en&ved=2ahUKEwj2rcjn7bT8AhV_KbcAHccfD8oQMygDegUIARDGAQ)


   # INSTALLATION
   This site was built using [For windows](https://gitforwindows.org/) download Git bash from here

   # A LIST OF GIT BASH COMMANDS:
   ## SETUP 
   **git config --global user.name “[name]”**

   - This command sets username, which aids in reviewing by whom the - changes were made. 

   **git config --global user.email “[email address]”**

   - This command sets an email address, this inturn helps in tracking by whom the commit or merge activity was made.

   **git config --global color.ui auto**

   - This command sets an automatic command line coloring effect for easy reviewing.  

   # CREATE AND INITIALIZE  
   **git init**

   - This command initialises the existing directory as a git repository

   **git init [repository name]**

   - This command is used to create or initiate a new git repository.

   **git clone [url]**

   - This command is used to obtain the entire repository or download existing source code from the URL provided. Basically makes an identical copy of the latest version of the repository in the local system.

   # STAGING AND COMMIT
   **git add [file]**

   - This command adds a file from the working tree to the Staging area / current branch.

   **git add [*]**

   - This command adds one or more files from the working tree to the Staging area / current branch.

   **git add.**

   - Stages all files in the entire repository to the Staging area / current branch.

   **git rm [file]**

   - This command deletes the existing file from your working directory.

   **git status**

   - This command lists all the files that have to be committed.

   **git diff** 

   - This command shows the changed contents that aren't staged.

   **git diff --staged** 

   - This command shows the changed contents that are staged but not committed.

   **git commit -m “[commit message]”**

   - This command records or snapshots the changes permanently in the version history of the repository.

   **git commit -a**

   - This command commits all the modified or created files to the repository.

   **git reset [file]**

   - This command unstage a file without any change in the working directory.

   **git reset [commit]**

   - This command undoes all the commits after the specific commit mentioned and preserves the changes locally.

   **git reset --hard [commit]**

   - This command discards all history and goes back to the specific commit mentioned ..

