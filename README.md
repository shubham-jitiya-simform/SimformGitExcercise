<b>SimformGitExcercise</b>

Complete this Git exercise by performing the following steps.

1. Android Repository: https://github.com/SimformSolutionsPvtLtd/SimformGitExcercise
2. Fork this Android repository to your Simform’s github account.
3. Add concerned person as collaborator and whenever you create PR don't forgot to add collaborator as reviewer.
4. Git flow initialization.
5. Create a "development" branch from the master branch.
6. Create a feature branch named “feature/Profile” from the development branch.
7. Create another feature branch named “feature/Authentication” from the development branch.
8. In the “feature/Authentication” :
    1. Create a login screen.
    2. Once it's done please commit your changes.
    3. Create a registration screen.
    4. Commit your changes.
    5. Create a forgot password screen.
    6.  Then save the changes locally (using git stash) 
    7. Now combine the first 2 commits(login & registration) into a single commit with a proper message (using git squash)
    8. Now unstash the forgot password changes from stash list. (using git stash)
    9.  Again perform the commit.
    10.  Then merge all commits into one with a proper message.
    11. Now Create PR from feature/Authentication branch to development branch and assign PR to concern reviewer.
    12.  Once above PR is approved and merged, Authentication feature is completed.
9. Now rebase development branch onto the feature/Profile, so that Profile branch became updated :
    1. Checkout from feature/Profile.
    2. Create a profile screen.
    3. Commit your changes with the proper message.
    4. Rename last commit and change commit message (This step needs to be performed on Call while sharing the screen).
    5. Create an Edit Profile screen.
    6.  Commit changes with proper message.
10. Now we require only 1st commit from feature/profile to development branch. (use cherrypick for this step)
11. Make sure all feature branches (previously created from the development branch) should up to date. (rebase)
12. Meanwhile, we got a serious issue on production build so we need to fix an issue and have to release :
    1. Create bugfix branch called bugfix/login_issue from development branch.
    2. Fix an issue faced on production build.
    3. Commit your changes.
    4. Rename commit message.
    5. Now create PR from bugfix branch to development branch.
13. Once above PR is approved and merged, make sure to update all the feature branches (previously created from the development branch) so all changes made on development branch will reflect in feature branches as well. (rebase)
