# Git and Github

All developers will use some kind of **version control system (VCS)**, a tool to allow them to collaborate with other developers on a project without the danger of them overwriting each other's work, and roll back to previous versions of the code base if a problem is discovered later on. The most popular VCS (at least among web developers) is **Git**, along with **GitHub**, a site that provides hosting for your repositories and several tools for working with them. This module aims to teach you what you need to know about both of them.

## Overview

VCSes are essential for software development:

- **Colaboration**: It is rare that you will work on a project completely on your own, and as soon as you start working with other people you start to run the risk of conflicting with each other's work — this is when both of you try to update the same piece of code at the same time. You need to have some kind of mechanism in place to manage the occurrences, and help avoid loss of work as a result.
- **Back-up**: When working on a project on your own or with others, you'll want to be able to back up the code in a central place, so it is not lost if your computer breaks.
- **Roll-back**: You will also want to be able to roll back to earlier versions if a problem is later discovered. You might have started doing this in your own work by creating different versions of the same file, e.g. `myCode.js`, `myCode_v2.js`, `myCode_v3.js`, `myCode_final.js`, `myCode_really_really_final.js`, etc., but this is really error-prone and unreliable.
- **Branches**: Different team members will commonly want to create their own separate versions of the code (called **branches** in Git), work on a new feature in that version, and then get it merged in a controlled manner (in GitHub we use **pull requests**) with the master version when they are done with it.

- VCSes provide tools to meet the above needs. [Git](https://git-scm.com/) is an example of a VCS, and [GitHub](https://github.com/) is a website + infrastructure that provides a Git server plus a number of really useful tools for working with git repositories individually or in teams, such as reporting issues with the code, reviewing tools, project management features such as assigning tasks and task statuses, and more.

>**Note**: Git is actually a *distributed* version control system, meaning that a complete copy of the repository containing the codebase is made on your computer (and everyone else's). You make changes to your own copy and then push those changes back up to the server, where an administrator will decide whether to merge your changes with the master copy.

## Prerequisites

To use Git and GitHub, you need:

- A desktop computer with Git installed on it (see the [Git downloads page](https://git-scm.com/downloads)).
- A tool to use Git. Depending on how you like to work, you could use a [Git GUI client](https://git-scm.com/downloads/guis/) (we'd recommend GitHub Desktop, SourceTree or Git Kraken) or just stick to using a terminal window. In fact, it is probably useful for you to get to know at least the basics of git terminal commands, even if you intend to use a GUI.
- A [GitHub account](https://github.com/join). If you haven't already got one, sign up now using the provided link.

In terms of prerequisite knowledge, you don't need to know anything about web development, Git/GitHub, or VCSes to start this module. However, it is recommended that you know some coding so that you have reasonable computer literacy, and some code to store in your repositories!

It is also preferable that you have some basic terminal knowledge, so for example moving between directories, creating files, and modifying the system PATH.

>**Note**: GitHub is not the only site/toolset you can use with Git. There are other alternatives such as GitLab that you could try, and you could also try setting your own Git server up and using it instead of GitHub. We've only stuck with GitHub in this course to provide a single way that works.

