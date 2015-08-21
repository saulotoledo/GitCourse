# How to push files to a (GitHub) remote repository

In this example, we will push a file to a remote repository.

After creating your GitHub repository, follow the steps below:

1. Open your favorite terminal application;
2. Create an empty folder;
3. Inside the created folder, type:

    ```
    git init
    ```
    
4. Create a file called README.md (see information about this file type
[here](https://help.github.com/articles/markdown-basics/));
5. Add and commit the file:

    ```
    git add README.md
    git commit -m "Your commit message"
    ```
    
Until now, you just have a local repository. Add a remote (called "origin"):

```
git remote add origin https://github.com/YourGitHubUsername/YourGitHubRepo.git
```

Finally, push your local modifications to the remote repository:

```
git push -u origin master
```

You can optionally add a version tag to your commit by using:

```
git tag 0.1.0
git push origin master --tags
```

For more information about Git, take a look at
[Git Documentation](http://git-scm.com/doc).

