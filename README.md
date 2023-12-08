# Project Contribution Guide

## Project Setup

1. **Clone the Repository:**

   - Navigate to the project repository on GitHub.
   - Click on the "Code" button and copy the repository URL.
   - Open your terminal and run the following command:

     ```bash
     git clone <repository-url>
     ```

   - Replace `<repository-url>` with the copied URL.

2. **Create a Branch:**

   - After cloning, navigate to the project directory using:

     ```bash
     cd <project-directory>
     ```

   - Create a new branch for your work:

     ```bash
     git checkout -b feature/<your-branch-name>
     ```

   - Choose a descriptive branch name related to your task.

## Contribute

1. **Task Execution:**

   - Work on a task based on an issue posted by other members.
   - After finishing the task, make sure to increment the name of the `.pkt` file from `netcom-project-1.pkt` to `netcom-project-2.pkt`

   - Make changes and commit them locally.

     ```bash
     git add .
     git commit -m "[Feature][<name>] - <commit message>"
     ```

1. **Push the Branch:**

   - Push your branch to the repository:

     ```bash
     git push origin feature/<your-branch-name>
     ```

1. **Create a Pull Request (PR):**

   - Visit the `repository` on GitHub.
   - Switch to your branch in the "Branch" dropdown.
   - Click on the "New Pull Request" button.
   - Provide a clear title and description for your PR.

     ```
     [Feature][<name>] - <title>
     ```

1. **Connect PR to Issue:**
   - If your PR addresses a specific issue, mention "Closes #<issue-number>" in the PR description.
   - This automatically closes the related issue when the PR is merged.

## Creating Issue

1. **Navigate to Issues:**

   - Go to the "Issues" tab on the GitHub repository.

2. **Create a New Issue:**

   - Click on the "New Issue" button.
   - Provide a descriptive title and detailed description of the issue.

     ```
     [Feature] - <new feature request>
     [Bug] - <Router 1 not working>
     ```

   - Assign labels, milestones, or assignees if necessary.
   - Submit the issue.
