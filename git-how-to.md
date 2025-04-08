# Git & GitHub Basics

Git is a distributed version control system enabling efficient code tracking and collaboration. Combined with GitHub, a cloud-based platform, it allows seamless project management.

## Key Steps

1. **Initial Setup**  
   Configure Git with your credentials:
   
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"

2. **SSH Authentication**
Generate an SSH key for secure GitHub access:

--> ssh-keygen -t ed25519 -C "your.email@example.com"
Add the public key (~/.ssh/id_ed25519.pub) to your GitHub SSH settings.

3. **Repository Workflow**

Clone a repository:

--> git clone git@github.com:username/repo-name.git

4. **Stage changes:**

--> git add filename

5. **Commit changes:**

--> git commit -m "Descriptive message"

6. **Push to remote:**

--> git push origin main

7. **Branching & Merging**
Create branches for features/fixes:

--> git checkout -b new-feature

Merge branches via pull requests on GitHub or locally:

--> git checkout main
--> git merge new-feature

8. **Syncing Updates**
Fetch/pull latest changes:

--> git pull origin main
