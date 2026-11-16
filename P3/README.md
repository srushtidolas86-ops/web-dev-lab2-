# P3: Feature-branch Git workflow

## Aim
Practise making a change on a separate branch and merging it into main.

## Steps
1. Check the current branch.
2. Create a feature branch.
3. Make a small change and check the status.
4. Stage and commit the change.
5. Push the feature branch and open a pull request on GitHub.
6. Review and merge the pull request.
7. Switch back to main and pull the latest changes.

## Commands
```bash
git branch
git switch -c feature/about-section
git status
git add .
git commit -m "Add about section"
git push -u origin feature/about-section
git switch main
git pull origin main
```

## What I learned
A feature branch keeps new work separate from the main version until it is ready to merge.
