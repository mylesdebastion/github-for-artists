# GitHub: Best Practices for Technical Artists
HELLO, WORLD! JASON HERE!!

## Table of Contents

1. [Introduction](#1-introduction)
2. [GitHub Basics](#2-github-basics)
3. [GitHub Desktop App](#3-github-desktop-app)
4. [Command Line Interface (CLI) Intro](#4-command-line-interface-cli-intro)
5. [Development Methodologies](#5-development-methodologies)
6. [Best Practices](#6-best-practices)
7. [Managing Tasks with GitHub Issues](#7-managing-tasks-with-github-issues)
8. [Recap and Conclusion](#8-recap-and-conclusion)
9. [Advanced Techinques](#advanced-techniques)

## 1. Introduction

### A. Why GitHub for artists?

- Welcome to the world of GitHub, where art meets code!
- GitHub provides a platform for artists to collaborate, track changes, and manage projects efficiently.
- Say goodbye to endless email chains, lost files, and version confusion.

### B. Overview of GitHub features for artists

- Version control: keep track of changes and revert when needed.
- Collaboration: work together on projects with ease.
- GitHub Issues: manage tasks, bugs, and feature requests.
- GitHub Desktop App: user-friendly interface for artists.

### C. Goals of the presentation

- Get acquainted with GitHub and its features.
- Learn best practices for using GitHub as a technical artist.
- Understand different development methodologies.
- Gain confidence in using GitHub to manage projects and collaborate with teammates.


## 2. GitHub Basics

### A. What is version control?

- Version control is a system that tracks changes to files over time.
- Enables multiple people to collaborate on a project.
- Allows you to revert to previous versions when needed.
- Git is a popular version control system, and GitHub is a platform built on top of it.

### B. Git vs. GitHub

- Git: a free, open-source distributed version control system.
- GitHub: a web-based platform for version control and collaboration using Git.
- Provides additional features like issue tracking, code review, and project management.

### C. Signing up and setting up

- Create a GitHub account at github.com (free for public repositories).
- Download and install GitHub Desktop App (desktop.github.com).
- Configure Git settings: name, email, and editor.


## 3. GitHub Desktop App

### A. Installation and setup

- Visit desktop.github.com and download the GitHub Desktop App.
- Install the app and log in with your GitHub account.
- Get ready to create and manage repositories with ease!

### B. Creating your first repository

#### 1. Documenting your project

- Click "New repository" and give it a name.
- Add a README.md file to describe the project and its purpose.
- Include setup instructions and any tools used.

#### 2. Setting up tools for the team project

- Create a repository to share tools and resources with your team.
- Keep the repository organized and up to date.

### C. Cloning an existing repository

- Clone an existing repository to work on a project with your team.
- Click "Clone a repository from the Internet" in the GitHub Desktop App.
- Choose the repository and select a local folder to store the files.
- Now you're ready to make changes and collaborate!

### D. Committing changes

- Make changes to your project files and watch the GitHub Desktop App track them.
- When you're ready, write a descriptive commit message and click "Commit."
- Remember: frequent, small commits are better than infrequent, large ones.

### E. Syncing and collaborating

- Push your changes to the remote repository by clicking "Push origin."
- Your teammates can now see and pull your changes.
- Collaboration made easy: work on different parts of the project without stepping on each other's toes!




## 4. Command Line Interface (CLI) Intro

### A. Why use the CLI?

- Faster and more efficient for some tasks.
- Automation possibilities with scripting.
- Better control and flexibility.
- CLI skills can impress your teammates! 😉

### B. Basic CLI commands

- git clone: copy a remote repository to your local machine.
- git status: check the status of your local repository.
- git add: stage changes for a commit.
- git commit: save changes with a descriptive message.
- git push: sync changes to the remote repository.

### C. Navigating repositories using the CLI

- Use your terminal or command prompt to navigate your local repository.
- Commands like cd (change directory) and ls (list) help you move around and see what's inside.
- Combine CLI commands to perform powerful Git operations with ease.


## 5. Development Methodologies

### A. What is trunk-based development?

- A development methodology where all developers work on a single branch (usually "main" or "master").
- Short-lived feature branches may be used but are merged back quickly.
- Faster integration and a more linear commit history.

### B. What is branch-based development?

- A development methodology where developers work on separate branches for features, bug fixes, or tasks.
- Branches are merged back into the main branch after completion and review.
- Allows for easier parallel development and code isolation.

### C. Pros and cons for artists

Trunk-based:
    + Faster integration, reducing merge conflicts.
    + Easier to maintain a consistent project state.
    - Requires more communication and coordination.

Branch-based:
    + Parallel development without interference.
    + Code isolation for better organization.
    - Potential for more complex merge conflicts.

### D. Choosing the right methodology

- Consider your project's size, team dynamics, and goals.
- Trunk-based development works well for small teams or fast-paced projects.
- Branch-based development is better for larger teams or projects with many parallel tasks.
- Remember: you can always adapt and change methodologies as needed.


## 6. Best Practices

### A. File organization

- Keep your repository clean and organized.
- Use folders and clear naming conventions for assets and files.
- Store documentation and resources in dedicated folders.
- Pro tip: a well-organized repository is a happy repository!

### B. Commit messages

- Write clear, concise, and informative commit messages.
- Describe the changes made and their purpose.
- Use the imperative mood: "Add new texture" instead of "Added new texture."
- Good commit messages make collaboration a breeze.

### C. Pull requests and code reviews

- Create pull requests to propose changes from a branch to the main branch.
- Describe the changes, their purpose, and any related issues.
- Assign reviewers to ensure quality and consistency.
- Review, discuss, and iterate on changes before merging.

### D. Merge conflict resolution

- Merge conflicts happen when two branches have conflicting changes.
- Don't panic! GitHub Desktop App and CLI can help you resolve them.
- Identify conflicting files and review the changes.
- Edit the files to keep the desired changes and remove conflict markers.
- Commit and merge your conflict-free code. Victory!


## 7. Managing Tasks with GitHub Issues

### A. What are GitHub Issues?

- GitHub Issues are a built-in tracking system for tasks, bugs, and feature requests.
- They help keep your project organized and on track.
- Issues can be assigned, labeled, and linked to pull requests.

### B. Managing tasks and bugs

- Create an issue for each task, bug, or feature in your project.
- Use labels to categorize and prioritize issues (e.g., bug, enhancement, documentation).
- Assign issues to team members and set deadlines with milestones.

### C. Collaborating with team members

- Use the @mention feature to notify team members in issue discussions.
- Collaborate, discuss, and resolve issues in a centralized location.
- Monitor project progress and team contributions using the Issues tab.
- Pro tip: the more you communicate, the smoother your project will run!




## 8. Recap and Conclusion

### A. Recap of key takeaways

- GitHub is a powerful platform for artists to collaborate, manage projects, and track changes.
- Embrace best practices like file organization, clear commit messages, and efficient collaboration.
- Choose the right development methodology for your project and team.
- Master the GitHub Desktop App and command line interface for maximum efficiency.

### B. Emphasis on the benefits of GitHub for artists

- GitHub helps artists work together seamlessly, keeping projects organized and up-to-date.
- Version control ensures that your assets and project files are always in sync and recoverable.
- GitHub Issues make task management and collaboration a breeze.

### C. Further resources and closing remarks

- Check out these resources for further learning:
    - GitHub Docs: docs.github.com
    - GitHub Guides: guides.github.com
    - Git Cheat Sheet: training.github.com/downloads/github-git-cheat-sheet.pdf
- Thank you for going through this learning material! Here's to successful projects and happy collaborations!




## Advanced Techniques

### Creating a New Repository via CLI

To create a new GitHub repository using the command line interface, you can use the GitHub API. Follow these steps:

1. **Generate a personal access token:**

   - Go to your GitHub account settings.
   - Click on "Developer settings" in the left sidebar.
   - Click on "Personal access tokens" and then the "Generate new token" button.
   - Give your token a description, select the "repo" scope, and click "Generate token."
   - Copy the generated token and store it safely; you won't be able to see it again.

2. **Use `curl` to make an API request to create a new repository:**

Replace `your_username` and `your_token` with your own GitHub username and the personal access token you generated in step 1.

```bash
curl -X POST -H "Authorization: token your_token" -H "Accept: application/vnd.github+json" https://api.github.com/user/repos -d '{"name": "your_repo_name", "description": "Your repository description", "private": false}'
```



### Creating a New Repository via CLI

To create a new GitHub repository using the command line interface, you can use the GitHub API. Follow these steps:

1. **Generate a personal access token:**

   - Go to your GitHub account settings.
   - Click on "Developer settings" in the left sidebar.
   - Click on "Personal access tokens" and then the "Generate new token" button.
   - Give your token a description, select the "repo" scope, and click "Generate token."
   - Copy the generated token and store it safely; you won't be able to see it again.

2. **Use `curl` to make an API request to create a new repository:**

Replace `your_username` and `your_token` with your own GitHub username and the personal access token you generated in step 1.

```bash
curl -X POST -H "Authorization: token your_token" -H "Accept: application/vnd.github+json" https://api.github.com/user/repos -d '{"name": "your_repo_name", "description": "Your repository description", "private": false}'
```

Replace "your_repo_name" and "Your repository description" with the desired name and description for your new repository. Set "private" to true if you want to create a private repository, or false for a public one.

This command sends a POST request to the GitHub API to create a new repository under your account with the specified name, description, and visibility.

Note: Sharing your personal access token can give others access to your account, so handle it carefully and avoid including it in scripts or public repositories.



### Creating GitHub Issues via CLI

To create new GitHub Issues using the command line interface, you can leverage the GitHub API. Follow these steps:

1. **Ensure you have a personal access token with the "repo" scope:**

   - If you don't have a personal access token, refer to the previous subsection on creating a new repository via CLI for instructions on how to generate one.

2. **Use `curl` to make an API request to create a new issue:**

Replace `your_username`, `your_repo`, and `your_token` with your own GitHub username, the target repository name, and your personal access token.

```bash
curl -X POST -H "Authorization: token your_token" -H "Accept: application/vnd.github+json" https://api.github.com/repos/your_username/your_repo/issues -d '{"title": "Issue Title", "body": "Issue Description"}'
```

Replace "Issue Title" and "Issue Description" with the desired title and description for your new issue. This command sends a POST request to the GitHub API to create a new issue in the specified repository.

Note: Sharing your personal access token can give others access to your account, so handle it carefully and avoid including it in scripts or public repositories.


### Using Git Large File Storage (LFS) for Artists

Git Large File Storage (LFS) is an extension for Git that replaces large files, such as images, videos, and other binary assets, with text pointers inside Git, while storing the actual file contents on a remote server. LFS is especially relevant for artists and can help improve the performance and management of repositories containing large assets.

1. **Why Git LFS is relevant to artists:**

   - Artists often work with large files like high-resolution images, videos, 3D models, and other binary assets.
   - Regular Git repositories can become slow and difficult to manage when handling large files.
   - Git LFS helps artists maintain a smooth workflow by efficiently tracking large files, making cloning and pulling faster.

2. **Getting started with Git LFS:**

   - Install Git LFS by following the instructions on the [official website](https://git-lfs.github.com/).
   - Navigate to your repository and run `git lfs install` to initialize LFS.
   - Use `git lfs track` followed by the file type pattern (e.g., `*.psd`, `*.blend`, `*.mp4`) to track specific file types.
   - Remember to commit the `.gitattributes` file created by Git LFS, as it keeps track of the file types you want to track with LFS.

**Note:** Git LFS usage may incur additional costs depending on your GitHub plan, and it may also affect your storage and bandwidth limits. Be sure to review the [Git LFS pricing](https://docs.github.com/en/github/setting-up-and-managing-billing-and-payments-on-github/about-billing-for-git-large-file-storage) before using it extensively.



### Using `.gitignore` for Technical Artists

A `.gitignore` file is used to specify files and folders that should not be tracked by Git. This can be particularly helpful for 3D Maya artists who want to exclude temporary, cache, or other unnecessary files from their repositories. 

1. **Why `.gitignore` is useful for technical artists:**

   - Helps keep the repository clean by excluding unwanted files.
   - Reduces repository size by avoiding the tracking of large temporary or cache files.
   - Simplifies collaboration by ensuring only relevant files are shared among team members.

2. **Creating and using a `.gitignore` file:**

   - Create a new text file named `.gitignore` in the root directory of your repository.
   - Add patterns (file types, folder names, or specific files) that you want to ignore, one per line.
   - Save the file and commit it to your repository.

3. **Typical examples for 3D Maya artists:**

```
# Ignore Maya temporary files
*.mayaSwatches
*.swatch

# Ignore Maya autosave files
*.ma.autosave
*.mb.autosave

# Ignore Maya cache files
cache/
*.mcx

# Ignore Maya viewport cache files
*.m3d

# Ignore rendered image sequences
images/
*.iff
*.exr
```


[Back to top](#table-of-contents)
