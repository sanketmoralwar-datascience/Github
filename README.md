# Github
# GitHub Tutorial for Beginners

This tutorial uses only the GitHub website, so you don't need to install anything. At the end, you'll have a real project online.

## Part 1: Create your account

1. Go to **github.com** and click **Sign up**.
2. Enter your email, a password, and a username. Pick something professional (e.g., `rahul-data`), since it becomes your profile link: `github.com/rahul-data`.
3. Verify your email.

## Part 2: Key terms (2 minutes)

- **Repository (repo):** a project folder stored on GitHub.
- **Commit:** a saved snapshot of your changes, with a short message.
- **Branch:** a separate copy of your project where you can try changes safely. The default branch is called `main`.
- **Clone:** download a repo to your computer.
- **Push / Pull:** send your changes to GitHub / get the latest changes from GitHub.
- **Fork:** copy someone else's repo into your own account.
- **Pull request (PR):** a request to merge your changes into another branch or repo.

## Part 3: Create your first repository

1. Click the **+** icon (top right) → **New repository**.
2. Name it `my-first-repo`.
3. Add a description: "Learning GitHub".
4. Choose **Public**.
5. Tick **Add a README file**.
6. Click **Create repository**.

## Part 4: Edit a file on the website

1. Click `README.md`.
2. Click the **pencil icon** (Edit).
3. Add a line like `Hello, this is my first repo!`
4. Click **Commit changes**, write a message ("Update README"), and confirm.

You just made your first commit.

## Part 5: Upload files

1. In your repo, click **Add file → Upload files**.
2. Drag in a notebook or any file.
3. Write a commit message ("Add notebook") and click **Commit changes**.

## Part 6: Create a folder

1. Click **Add file → Create new file**.
2. In the name box, type `notebooks/test.txt`. Typing the slash creates the folder.
3. Add any text and commit.

## Part 7: Try a branch and pull request

This is how professionals work, and it's worth knowing early.

1. Click the **main** dropdown (top left of the file list), type `add-notes`, and click **Create branch**.
2. Edit a file or add a new one while on this branch, then commit.
3. A banner appears: **Compare & pull request**. Click it.
4. Add a title and click **Create pull request**.
5. Click **Merge pull request → Confirm merge**.

Your changes are now on `main`. On real teams, someone reviews the PR before merging.

## Part 8: Polish your profile

1. Create a repo named exactly the same as your username (e.g., `rahul-data`) with a README. It appears on your profile page.
2. Write a short intro and link your best projects.
3. **Pin** your top 3-6 repos: go to your profile → **Customize your pins**.

## Part 9: Using Git from your computer (when you're ready)

Install Git from **git-scm.com**, then the core workflow is:

```bash
git clone https://github.com/yourname/my-first-repo.git
cd my-first-repo
# make changes to files...
git add .
git commit -m "Describe what you changed"
git push
```

To get updates made elsewhere:

```bash
git pull
```

Useful extras:

```bash
git status      # see what changed
git log         # see commit history
git checkout -b new-branch   # create and switch to a branch
```

## Part 10: Good habits

- Write clear commit messages ("Fix missing-value handling", not "update").
- Commit small and often.
- Never upload passwords or API keys.
- Add a `.gitignore` for files you don't want tracked (GitHub offers a Python template when creating a repo).
- Keep a README in every project.

## Practice exercise (15 minutes)

1. Create a repo called `data-science-journey`.
2. Add a README describing your 12-week plan.
3. Upload one Colab notebook using **File → Save a copy in GitHub**.
4. Create a branch, edit the README, and merge it through a pull request.

## Free resources to go further

- **GitHub Skills** (skills.github.com): interactive, free courses that run inside GitHub itself.
- **GitHub Docs** quickstart: docs.github.com
- **Git & GitHub Crash Course** videos on YouTube (freeCodeCamp has a good one).

I can also walk you through any step in more detail, or help you write the README for your first data science project.
