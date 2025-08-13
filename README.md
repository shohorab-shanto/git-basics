# My First Git Project

This is a simple project to practice version control using Git and GitHub.

## Features
- Initialize a Git repository
- Create and commit files
- Push to GitHub

---

Author: Shohorab Shanto

# GitHub Actions CI/CD
This repo has a simple GitHub Actions workflow that runs on push and pull request to main.

Jobs:

test_job – Checks out the code and prints the contents of hello.txt.

build_job – Runs after test_job and checks out the code again.
(Optional Node.js setup is commented out)

Flow:
test_job → build_job (sequential execution)
