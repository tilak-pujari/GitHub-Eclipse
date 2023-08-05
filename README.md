
# GitHub-Eclipse
step-by-step instructions for pushing and pulling changes to/from a GitHub repository using the Eclipse IDE:

## Pushing Changes to GitHub:

1. Clone the Repository:
   - Open Eclipse IDE.
   - Go to `Window` > `Show View` > `Other`.
   - Search for "Git" and select `Git Repositories`, then click `Open`.
   - In the `Git Repositories` view, click the "Clone a Git repository" button.
   - Enter the repository URL and your GitHub credentials.
   - Choose the destination directory where the repository will be cloned.
   - Click `Next` and follow the prompts to complete the cloning process.

2. Make Changes:
   - Open your project in Eclipse and make the desired changes to your files.

3. Commit Changes:
   - Go to the `Git Staging` view.
   - Select the files you want to commit.
   - Enter a commit message describing your changes.
   - Click the `Commit` button.

4. Push Changes to GitHub:
   - In the `Git Staging` view, click the `Push` button.
   - Ensure the correct remote repository is selected.
   - Click `Next`, review the changes, and click `Finish`.

## Pulling Changes from GitHub:

1. Open Project:
   - Open Eclipse IDE.

2. Fetch and Merge:
   - Go to the `Git Staging` view.
   - Click the `Fetch from Upstream` button to fetch the latest changes from the remote repository.
   - Select the branch you want to update and click `OK`.
   - Once the fetch is complete, right-click on your local branch and choose `Merge` to merge the fetched changes into your branch.

3. Resolve Conflicts (if any):
   - If there are conflicts, Eclipse will highlight them in your files.
   - Right-click on the conflicted file and choose `Team` > `Merge Tool`.
   - Resolve conflicts and save the file.

4. Commit Merged Changes:
   - Go to the `Git Staging` view.
   - Select the merged files.
   - Enter a commit message describing the merge.
   - Click the `Commit` button.

# Github-Gitbash/Git/Command Line
## Pushing Changes to GitHub:

1. Goto location where our code present
   cd projects/my-project
2.Initialize git repository
   git init
3. Add Code to git stagin area
    git add *
4. Commit our code to repository
    git commit -m "Initial commit"
5. Push the code to git repository
   git push -u origin master


## Pulling Changes from GitHub:
1. Create an empty folder where you want to pull the git code
2. Initilize git repository
   git init
3. Add the remote git address
   git remote add origin master git_project_url
4. Pull the Code from github to your local repository
   git pull origin master