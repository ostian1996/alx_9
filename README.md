# alx_9

0x01. Git
=========
Resources
---------

**Read or watch:**

-   [Resources to learn Git](https://alx-intranet.hbtn.io/rltoken/EC5rb6yWBWllPB-T8rd0SQ "Resources to learn Git")
-   [About READMEs](https://alx-intranet.hbtn.io/rltoken/yM5FZakIhHB2TWO1PN2PZg "About READMEs")
-   [How to write a Git commit message](https://alx-intranet.hbtn.io/rltoken/SihXX88mKA9TFaIebKX3Rw "How to write a Git commit message")

**Resources for advanced tasks** (Read only after finishing the mandatory tasks):

-   [Learning branching](https://alx-intranet.hbtn.io/rltoken/hBgLCXoQaGTcOwr_kmCoEA "Learning branching")
-   [Effective pull requests and other good practices for teams using GitHub](https://alx-intranet.hbtn.io/rltoken/xhKV_qX3eXvyePzeNraEGw "Effective pull requests and other good practices for teams using GitHub")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](https://alx-intranet.hbtn.io/rltoken/Rfy6VuvRfNAau31z1J_b-w "explain to anyone"), **without the help of Google**:

### General

-   What is source code management
-   What is Git
-   What is GitHub
-   What is the difference between Git and GitHub
-   How to create a repository
-   What is a README
-   How to write good READMEs
-   How to commit
-   How to write helpful commit messages
-   How to push code
-   How to pull updates
-   How to create a branch
-   How to merge branches
-   How to work as collaborators on a project
-   Which files should and which files should not appear in your repo

### Copyright - Plagiarism

-   You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
-   You will not be able to meet the objectives of this or any following project by copying and pasting someone else's work.
-   You are not allowed to publish any content of this project.
-   Any form of plagiarism is strictly forbidden and will result in removal from the program.

Requirements
------------

### General

-   A `README.md` file at the root of the `alx-pre_course` repo, containing a description of the repository
-   A `README.md` file, at the root of the folder of *this* project (i.e. `0x01-git`), describing what this project is about
-   **Do not use GitHub's web UI**, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won't be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
-   Your answer files should only contain the command, and nothing else

More Info
---------

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main

```

### Quiz questions

#### Question #0

You have the following files in your project directory:

```
julien@ubuntu:/tmp/git_project$ ls
0-test  0-test~ #0-test# file1  file2

```

You've edited `0-test` and you want to add it to your GitHub repo. What is the correct command to add **only** `0-test`?

-   [ ]

    `git add .`

-   [ ]

    `git add -N 0-test`

-   [ ]

    `git add 0-test`

#### Question #1

What command can you use to see what changes have been staged, which haven't, and which files aren't being tracked by Git?

-   [ ]

    `git init`

-   [ ]

    `git status`

-   [ ]

    `git checkout`
