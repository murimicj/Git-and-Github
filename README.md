# Git-and-Github
Git & GitHub Advanced Assignment
Objective:
You will simulate a real-world collaborative development workflow by working on a GitHub repository, handling branching, merging, rebasing, resolving conflicts, and contributing to an open-source project.

Task 1: Repository Setup & Branching
Fork & Clone:

Fork the following repository: GitHub Sample Repo (Use any public repo or create your own if none is provided)
Clone it to your local machine:
bash
Copy
Edit
git clone https://github.com/YOUR_USERNAME/sample-repo.git
cd sample-repo
Create & Switch to a New Branch:

Create a feature branch named feature-update and switch to it:
bash

git checkout -b feature-update

Task 2: Modify Files & Commit History Management
Modify a File:

Open the README.md file and add a new section titled "Contributions" with your name.
Save the changes and stage them:
bash

git add README.md
Make Multiple Commits:

Commit your changes with a meaningful message:
bash

git commit -m "Added Contributions section with my name"
Modify another file (e.g., index.html or script.js) and commit again.
Amend the last commit message:
bash

git commit --amend -m "Updated Contributions section and modified index.html"
Use Interactive Rebase to Squash Commits:


Task 3: Merging & Conflict Resolution
Pull Latest Changes from main Branch:

Switch back to the main branch:
bash

git checkout main
Pull the latest changes:
bash

git pull origin main
Merge Your Feature Branch into Main:

Attempt to merge your feature-update branch into main:
bash

git merge feature-update
If merge conflicts occur:
Identify them using git status
Open conflicting files and manually resolve the issues
Stage the resolved files:
bash

git add .
Complete the merge:
bash

git commit -m "Resolved merge conflicts and merged feature-update into main"
Task 4: Push & Pull Request (PR) Submission
Push Changes to GitHub:

Push the updated main branch:
bash

git push origin main
Push the feature-update branch:
bash

git push origin feature-update
Open a Pull Request (PR):

Go to GitHub and navigate to your repository.
Open a Pull Request (PR) from feature-update to main.
Add a title and description explaining your changes.
Request a code review.
Task 5: Contribute to Another Person’s Repository (Bonus Task)
Find a Repository with Open Issues:

Search for repositories with a good first issue or help wanted label.
Clone and work on the issue.
Fork & Contribute:

Fork the repository.
Clone it locally and create a new branch.
Fix the issue and commit your changes.
Open a Pull Request to contribute to the original repository.
