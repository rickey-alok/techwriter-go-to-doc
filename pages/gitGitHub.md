# Git & Gihub - Cheatsheet

## Git (Global Information Tracker) <img src="./../img/git-logo.png" alt="git" width="9%" height="9%" style="float:right">

- What
  - an open source
    - so it is free to use and developers can modify the source code to suit their needs
  - distributed version-control system, for software development mainly.
    - meaning there is no central point of control
  - but not a programming language
  - develop by **Linus Torvalds** in 2005
- Why
  - Collaboration
    - allows multiple developers to work on the same project at the same time without interfering with one another
  - Branching
    - allows developers to create branches of a project, so they can make changes without affecting the main version of the project.
  - Speed
    - fast and efficient system which allows developers to work quickly and seamlessly on projects
  - Security
    - uses encryption to secure data transfer and storage, which helps keep sensitive information safe.

## Github <img src="./../img/github-logo.png" alt="git" width="9%" height="9%" style="float:right">

a platform for hosting and collaborating on Git repositories

## Workflow

![Git and GitHub](./../img/workflow-git.drawio.png "overview")

<p style="text-align: center;"><u>Git&GitHub workflow</u></p>

### One time commands

- Initialize repository: `git init`
- Add remote repo to local server: `git remote add origin <url (http or SHH)>`
- Clone remote repo to local server: `git clone <url (http or SHH)>`
- Set email: `git config --global user.email "xyz@gmail.com"`
- Set name: `git config --global user.name "yourName"`
