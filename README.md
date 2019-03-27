1. Create a new repository on GitHub. Do not initialize the new repository with README, license, or gitignore files

2. Open Git Bash.

3. Change the current working directory to your local project.

4. Initialize the local directory as a Git repository.
$ git init

5. Add the files in your new local repository 
$ git add .

6. Commit the files that you've staged in your local repository.
$ git commit -m "First commit"

7. At the top of your GitHub repository's Quick Setup page, Copy the remote repository URL.

8. In the Command prompt, add the URL for the remote repository where your local repository will be pushed
$ git remote add origin remote repository URL
$ git remote -v

9. Push the changes in your local repository to GitHub.
$ git push origin master

10. Check your project status
$ git status
