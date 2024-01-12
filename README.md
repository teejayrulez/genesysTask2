# Learnable Assignment

### Explain version control

Version control also known as source control, is the practice of tracking and managing changes to software code. It is a software tool that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments. Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

### Explain differnce between git and github

Git and GitHub are both popular tools for developers, but they are not the same thing.

1. Git is a version control system that helps you track changes in your source code while GitHub is a hosting service that provides a web-based interface for managing your Git repositories.

2. Git is a software that enables you to create and maintain local repositories of your code on your own computer. You can use Git to commit changes, branch and merge different versions, and rollback to previous states if needed while GitHub is a platform that allows you to host and share your Git repositories online. You can use GitHub to collaborate with other developers, manage issues and pull requests, review code, and access various tools and integrations.

3. Git is open-source and free to use for anyone. It was first released in 2005 by Linus Torvalds, the creator of Linux while GitHub is owned by Microsoft and offers both free and paid plans for users. It was launched in 2008 by Tom Preston-Werner, Chris Wanstrath, and PJ Hyett.

### List 3 other github alternatives

- Gitbucket

- TaraVault

- Bitbucket

### Explain the difference between git fetch and git pull

1. Git fetch only retrieves the changes from the remote repository and stores them in your local repository while git pull retrieves the changes and also merges them into your current branch.

2. With git fetch you can review the changes from the remote repository before integrating them into your local repository while git pull simplifies your workflow by automatically updating your local branch with the remote changes.

### Explain in simple terms git rebase and the command for

Git rebase is the linear process of merging. It is the process of moving or combinig a sequence of commits to a new base. It looks like a single, completely linear timeline of changes. The Git rebase command moves a branch to a new location at the head of another branch. Unlike the Git merge command, rebase involves rewriting your project history. It's a great tool, but don't rebase commits other developers have based work on. The Git rebase command achieves its aims in a completely different way. It takes all of the commits from the branch you're going to rebase and replays them onto the end of the branch you're rebasing onto.

#### The Commands

For launching a standard git rebase

- git rebase <base>

For launching an interactive git rebase

- git rebase --interactive <base>

Check rebase status

- git status

Skip the changes

- git rebase --skip

### Explain in simple terms git cherry-pick and the command for it

Git cherry-pick is apowerful command that enables arbitrary git commits to be picked by reference and appende to the current working HEAD. Cherry picking is the act of picking a commit from a branch and applying it to another. Git cherry-pick can be useful for undoing changes.

#### The Commands

Replaceing a committed hash from other branches

- git cherry-pick <commit-hash>

Replacing from a public-branch

- git cherry-pick -x <commit-hash>
