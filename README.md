In your project directory if you type in "ls -a"
We will see a folder called ".git" in our terminal

Remember: ".git" gets there after we initialize a folder with the command "git init"

In React environment, the project is already initialized. To check where we are pushing to we run the command "git remote -v". If we don't see anything in our terminal that means we are not pushing to any remote repository.

1.) Create a new repository on GitHub.com
2.) Make sure that you skip the step of Initializing your new repo
3.) Use the second block of code since we are pushing an existing repository
4.) Go into the terminal, make sure the terminal is inside your project directory and then run the commands you copied from GitHub
5.) We should see something similar to this:

              Enumerating objects: 22, done.
              Counting objects: 100% (22/22), done.
              Delta compression using up to 16 threads
              Compressing objects: 100% (22/22), done.
              Writing objects: 100% (22/22), 188.35 KiB | 8.97 MiB/s, done.
              Total 22 (delta 0), reused 0 (delta 0)
              To github.com:tmarcelojr/react-state-store.git
              * [new branch]      main -> main
              Branch 'main' set up to track remote branch 'main' from 'origin'.

6.) Refresh your GitHub repo to make sure that your project got uploaded
7.) To see our up to date changes we need to run the command "git add ."
8.) Make your commit message with command git commit -m "Updated React Store"


===== GIT PUSH =====
1.) When we pasted git commands from GitHub it had a command that looked like this: 
            git push -u origin main
2.) "-u" is short for "--set-upstream" which just means that we are setting a reference to the branch main
3.) This allows us to write "git push" and the whole command