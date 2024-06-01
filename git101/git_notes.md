## Index

0. [Best Resources to learn git](#resources-to-learn-git-and-github)
1. [What is Git?](#what-is-git)
2. [What is Versioning System?](#what-is-versioning-system)
3. [Why Git?](#why-git)
4. [GitHub](#github)
5. [Levels of Git Configuration](#levels-of-git-configuration)
6. [Git Fetch vs Git Pull](#git-fetch-vs-git-pull)
7. [Git Merge vs Git Rebase](#git-merge-vs-git-rebase)
8. [Pre-Commit Hooks](#pre-commit-hooks)
9. [Git Workflow](#git-workflow)
10. [Git Best Practices](#git-best-practices)

## Resources to learn git and github

#### Beginner: just want to get started in git and do a quick hands on:
- https://youtu.be/8JJ101D3knE?si=cSj7sryFIFbguFQS


#### Mastery: deep dive into git and learn intermediate/advanced concepts
- https://youtu.be/zTjRZNkhiEU?si=PmjE14UdJw7j_fbY
- https://learngitbranching.js.org/

## What is Git?

Git is a distributed version control system designed for tracking changes in source code during software development. It allows multiple developers to collaborate on projects, managing changes efficiently and enabling easy branching, merging, and versioning.

## What is Versioning System?

A versioning system, like Git, tracks changes made to files over time. It captures a history of modifications, allowing users to revert to previous states, compare changes, and collaborate effectively. Versioning systems are essential for managing codebases and ensuring project stability.

## Why Git?

Git offers numerous benefits, including:
- Distributed architecture for offline work and fast operations.
- Efficient branching and merging capabilities for parallel development.
- Strong support for collaboration among developers.
- Rich set of tools for tracking changes, resolving conflicts, and managing workflows.

## GitHub

GitHub is a web-based platform built around Git, offering hosting services for software development projects. It provides features like version control, issue tracking, code review, and project management. GitHub facilitates collaboration among developers, fostering open-source contributions and enabling efficient software development workflows.


## Levels of Git Configuration

### 1. System-level Configuration

- Applies to all users on the system.
- Stored in the system-wide Git configuration file (`/etc/gitconfig`).

### 2. Global Configuration

- Applies to a specific user.
- Stored in the user's home directory (`~/.gitconfig` or `~/.config/git/config`).

### 3. Repository-level Configuration

- Applies to a specific Git repository.
- Stored in the repository's `.git/config` file.

## Git Fetch vs Git Pull

### Git Fetch

- Retrieves changes from the remote repository to the local repository.
- Does not merge changes into the working branch.
- Updates remote tracking branches.
- Useful for reviewing changes before merging.

### Git Pull

- Retrieves and merges changes from the remote repository to the working branch.
- Performs a fetch followed by a merge.
- Convenient for quickly integrating remote changes into the local branch.

## Git Merge vs Git Rebase

### Git Merge

- Integrates changes from one branch into another.
- Preserves the commit history of both branches.
- Creates a merge commit to combine the changes.

### Git Rebase

- Rewrites the commit history by moving, or "rebasing," commits to a new base commit.
- Results in a linear history, making it appear as if all the changes were made sequentially.
- Useful for maintaining a clean and linear history, but can cause conflicts if used improperly.

## Pre-Commit Hooks

- Pre-commit hooks are scripts or commands executed automatically before a commit is finalized.
- They allow for custom checks or tasks to be performed, such as code linting, running tests, or checking for sensitive information.
- If a pre-commit hook fails (returns a non-zero status), the commit process is aborted.

## Git Workflow

- Git workflow refers to the methodology or pattern a team follows for collaborating using Git.
- Common workflows include centralized, feature branch, Gitflow, forking, and pull request workflows.
- Each workflow defines how branches are used, how changes are integrated, and how releases are managed.

## Git Best Practices

- Use descriptive commit messages.
- Commit early and often to capture incremental changes.
- Keep commits focused on a single logical change.
- Utilize branches for feature development or bug fixes.
- Regularly pull changes from remote repositories to stay up-to-date.
- Use interactive rebasing to clean up commit history before merging.
- Collaborate effectively by using pull requests and code reviews.
- Document and follow a consistent branching strategy suitable for your project.
