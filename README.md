Step 1: Create a folder in ~/Documents called blackCodherBootCamp
Step 2. Inside the blackCodherCamp folder create a local git repository called introToGit
Step 3. Add a text file to the repo called it exampleFile
Step 4. Commit the change
Step 5. Create a new repository on GitHub
-
Step 6. In your local git repo enter the following commands:
- git remote add origin https://github.com/<yourGitName>/<yourRepoName>.git
- Git push -u master origin
Step 7: Refresh your GitHub repo, what do you see? What does “-u”, “master” and
“origin” mean or do?
  
     Origin is a remote repository - that all team members can make changes to.
     Master is a local branch where we first initiate git and then we use to make commits - changes in the master can pull/push into a remote.
     origin/master: is a remote branch, which has a local branch named master on a remote named origin.
    " -u " Means to set upstream
