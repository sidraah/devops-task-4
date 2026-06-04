### Objective
Manage a DevOps project using Git best practices, including version control, branching strategies, pull requests, tags, and project documentation.

## Tools Used
* Git
* GitHub
* Visual Studio Code
  
## Repository Setup
The project repository was initialized locally using Git and connected to a remote GitHub repository.

### Git Initialization
```bash
git init
git remote add origin <repository-url>
git push -u origin main
```

## Branching Strategy
The following branches were created and used during development:

| Branch         | Purpose                                             |
| -------------- | --------------------------------------------------- |
| main           | Production-ready code                               |
| dev            | Development branch                                  |
| feature-readme | Feature branch for README and documentation updates |

### Branch Creation
```bash
git checkout -b dev
git checkout -b feature-readme
```

## Project Structure
```text
devops-project/
│
├── README.md
├── .gitignore
│
└── docs/
    └── tasks.md
```

## Git Workflow Followed

1. Initialized local repository.
2. Added project files.
3. Created and pushed the main branch.
4. Created a development branch.
5. Created a feature branch.
6. Made changes and committed updates.
7. Pushed feature branch to GitHub.
8. Created Pull Requests.
9. Merged feature branch into dev.
10. Merged dev into main.
11. Created a release tag.
12. Documented project tasks.

## Pull Request Process
### Pull Request 1
* Source Branch: feature-readme
* Target Branch: dev
* Purpose: Add README and project documentation

### Pull Request 2
* Source Branch: dev
* Target Branch: main
* Purpose: Merge completed development work into production branch

## .gitignore Configuration
The following files and folders were excluded from version control:
```gitignore
.env
*.log
*.tmp
.vscode/
node_modules/
```

## Git Tag
A release tag was created for project versioning.

```bash
git tag -a v1.0 -m "Project completed"
git push origin v1.0
```
### Release Version
* v1.0

## Documentation
Project documentation is maintained in:

```text
docs/tasks.md
```
This file contains task progress, project updates, and completion records.

### project repository link :


## Learning Outcomes
Through this project, I learned:
* Git version control fundamentals
* Repository initialization and remote management
* Branching strategies
* Pull Request workflow
* Merge operations
* Git tags and versioning
* Documentation using Markdown
* Collaboration practices using GitHub
DevOps Internship Task Submission

