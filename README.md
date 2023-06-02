# Git4Devs: **GitHub For Game Development**
[![Twitter Follow](https://img.shields.io/twitter/follow/youtube?label=Follow&logo=Github&style=social)](https://github.com/himanshuskyrockets) [![Twitter Follow](https://img.shields.io/twitter/follow/youtube?label=subscribe&logo=youtube&style=social)](https://www.youtube.com/@ExplorerArts) [![Medium.com](https://img.shields.io/badge/medium-.com-blue)](https://medium.com/@Clubwritter) [![Twitter Follow](https://img.shields.io/twitter/follow/youtube?label=Follow&logo=twitter&style=social)](https://twitter.com/superman_space) [![Support](https://img.shields.io/badge/-Support-green)](https://github.com/sponsors/himanshuskyrockets/)
 
![Image](https://github.githubassets.com/images/modules/logos_page/Octocat.png)

Welcome to the beginner's guide on using GitHub for Unity game development projects. GitHub is an incredibly useful tool that enables game developers to collaborate effectively, manage code versions, and track changes easily. Whether you're a newbie or a professional, this guide will walk you through the process step by step. Let's get started!

## **Table of Contents**

- **[Step 1: Create a GitHub account](#step-1-create-a-github-account)**
- **[Step 2: Create a new repository](#step-2-create-a-new-repository)**
- **[Step 3: Clone your repository](#step-3-clone-your-repository)**
- **[Basic Git Commands](#basic-git-commands)**
- **[Advanced Git Commands](#advanced-git-commands)**
- **[Adding a Local Repository to GitHub using Git](#adding-a-local-repository-to-github-using-git)**
- **[Difference between Git and GitHub](#difference-between-git-and-github)**
- **[Conclusion](#conclusion)**

## **Step 1: Create a GitHub account**

To use GitHub, you need to create an account. Follow these steps:

1. Go to **[github.com](https://github.com/)** and click on "Sign up."
2. Choose either a free account or sign up for a paid plan.

## **Step 2: Create a new repository**

Once you have a GitHub account, you can create a new repository for your Unity game project:

1. Click on the "New repository" button on your GitHub dashboard.
2. Follow the instructions to create a new repository.

## **Step 3: Clone your repository**

To work with your repository locally on your machine, you need to clone it using the following Git command:

```

git clone [repository URL]

```

Replace **`[repository URL]`** with the URL of your GitHub repository. For example:

```

git clone https://github.com/himanshuskyrockets/Unity_OpenAI

```

## **Basic Git Commands**

Now that you have your repository set up and cloned locally, it's time to learn some basic Git commands:

1. **git add**: Use this command to add files to the staging area.
    
    ```
  
    git add [filename]
    
    ```
    
    Replace **`[filename]`** with the name of the file you want to add.
    
2. **git commit**: Use this command to commit your changes to the repository.
    
    ```
   
    git commit -m "Added a new script"
    
    ```
    
    Replace **`"Added a new script"`** with a brief message describing your changes.
    
3. **git push**: Use this command to push your changes to the remote repository on GitHub.
    
    ```
 
    git push origin master
    
    ```
    
    This command pushes the changes to the "master" branch of the "origin" repository.
    
4. **git pull**: Use this command to pull changes from the remote repository.
    
    ```
    
    git pull origin master
    
    ```
    
    This command pulls changes from the "master" branch of the "origin" repository.
    

To see a full list of available shortcuts on GitHub, press **Shift + /** to open the keyboard shortcuts menu.

## **Advanced Git Commands**

Here are some advanced Git commands that can enhance your workflow:

1. **git branch**: Use this command to create, list, or delete branches in your repository.
    
    ```
    
    git branch [branchname]
    
    ```
    
2. **git merge**: Use this command to merge changes from one branch into another.
    
    ```
    
    git merge [branchname]
    
    ```
    
    This command merges the changes made in the **`[branchname]`** branch into the current branch.
    
3. **git stash**: Use this command to save changes that are not ready to be committed.
    
    ```
  
    git stash save "Work in progress"
    
    ```
    
    This command saves your changes with the message "Work in progress."
    
4. **git revert**: Use this command to undo a commit.
    
    ```
    
    git revert [commit hash]
    
    ```
    
    This command reverts the changes made in the commit with the specified hash.
    

## **Adding a Local Repository to GitHub using Git**

Adding a local repository to GitHub using Git is a straightforward process. Follow these steps:

Step 1: Initialize the local directory as a Git repository.

```

git init -b main

```

Step 2: Add the files in your new local repository.

```

git add .

```

Step 3: Commit the files that you've staged in your local repository.

```

git commit -m "First commit"

```

Congratulations! You have successfully added your local repository to GitHub.

## **Difference between Git and GitHub**

Git and GitHub are closely related but serve different purposes:

**Git** is a version control system that allows you to track changes made to your code over time. It helps you manage different versions of your code and collaborate with others.

**GitHub**, on the other hand, is a web-based hosting service that uses Git for version control. It provides a platform for developers to store and manage their Git repositories online. GitHub offers additional features like bug tracking, project management, and team collaboration tools, making it easier for developers to work together on projects.

Think of GitHub as a social network for developers, where they can share and collaborate on code with other developers.

## **Conclusion**

GitHub is an invaluable tool for game developers collaborating with others or needing to track code changes. This guide covers the basics of using Git commands for Unity game development projects. Remember, there are many more advanced features to explore and master. With practice, you can enhance your Git knowledge and accelerate the game development process.

You can Follow me on GitHub: **[ME 📧)](https://github.com/himanshuskyrockets)**


## **Additional Resources**

For more in-depth information and tutorials on using Git, GitHub, and Unity for game development, refer to the following resources:

- **[Git Documentation](https://git-scm.com/doc)**
- **[GitHub Guides](https://guides.github.com/)**
- **[Unity Documentation](https://docs.unity3d.com/)**

Explore these resources to expand your knowledge and master the tools for efficient game development.
