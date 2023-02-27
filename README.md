This repo is for git practice only.
If a repo is created locally first, the following steps will link the local repo to a Github repo:

git remote add origin YOUR-GITHUB-LINK-HERE
git branch -M main
git push -u origin main

(1) git remote add origin YOUR-GITHUB-LINK-HERE adds a reference from your local git repo to your Github repo. We gave this reference a name: origin. So now we can perform commands like git pull origin and git knows to go to that Github link and pull changes from that repository.

(2) git branch -M main renames our default branch to main instead of master (the previous default).

(3) git push -u origin main pushes the local changes on our repo over to Github. Our two repositories should now be in sync.