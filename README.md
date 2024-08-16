# This is the guide to cloning and forking the repository for a project.

## Cloning a repository

1. Go to the repository you want to clone.
2. Click on the green "Code" button.
3. Copy the URL.
4. Open your terminal.
5. Change the current working directory to the location where you want the cloned directory.
6. Type `git clone`, and then paste the URL you copied in step 3.
7. Press Enter to create your local clone.

### Raise a Pull Request in a cloned repository

1. Go to the cloned repository.
2. Open your cloned reopository in VS Code.
3. Open the terminal in VS Code.
4. Type `git pull origin main` to get the latest changes from the repository.
2. Type `git checkout -b "your-name"` to create a new branch.
6. Go back to the repository inside VS Code.
3. Make a new folder with your name. Add a new file, call it `README.md`, and write your name in it.
4. Add and commit the changes using the following commands:
   - `git add .`
   - `git commit -m "Added my name"`
5. Push the changes to the repository using the following command:
   - `git push -u origin your-name`
6. Go to the repository on GitHub.
7. Click on the "Pull Request" button.
8. Add a title and description to your pull request.
9. Click on the "Create Pull Request" button.
10. Send your PR in Slack to review.