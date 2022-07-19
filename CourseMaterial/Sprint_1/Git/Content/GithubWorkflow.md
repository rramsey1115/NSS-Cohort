# Github Workflow

Your instruction team will show you the Github workflow interactively in class based on the diagram below.

The actions they will demonstrate are:

- Cloning a repo
- Creating new branches to work on
- Making changes and pushing up branches to Github
- Creating a pull request for those changes in Github
- Code reviewing a pull request
- Approving and merging the pull request for a teammate
- Pulling the new code into your local branches
- Creating a new branch after finishing

![](../Images/GitHub-Flow.png)

## Terms To Know

**Pull Request**: Also known as a PR, a pull request is an action you can take in Github where you flag a branch with code changes to be approved and merged into your main branch.

When you open a PR you will send the link to your teammates and one of them will look over the code and either approve it or ask for changes. This helps to make sure that every teammate has agreed on the code that is added to the main branch.

## Group Project Github Workflow

### Cloning A Repo & Getting Started

Let's follow the diagram above starting from the top. We can see that we have two teammates working in one repo. The first thing they are going to do is clone down the repo to their local machine.

![](../Images/GitHub-Flow-1.png)

Now they have two local copies of the main Github branch that they can work off of.

### Create A Branch

As we have learned in our Git & Github basics course we don't EVER want to work on the main branch. When our two teammates want to start new work they will create a branch off of their local main branch.

![](../Images/GitHub-Flow-2.png)

Now they can both begin coding! They have two separate branches on their local machines that they can work on.

### Pushing Up Work For Review

Let's say that Teammate 2 finishes their work and is ready to push up their branch.

They can now push their work up to Github to be reviewed and merged. We can see in the diagram that they push their code, create a pull request, and ask their other teammate for a code review.

![](../Images/GitHub-Flow-3.png)

If the teammate thinks that the code looks good they will then approve and merge the PR.

Afterwards, Teammate 2 checkouts out to their local main branch. They are done with the branch they were working on and are ready to start a new one.

### Pulling New Code In Locally

As you can see on the other side of the diagram, Teammate 1 is still working on their branch and will need to make sure to include the code that Teammate 2 just merged into the main branch in Github.

Just because the code is in Github does not mean that either Teammate has that code on their local machines. They have to pull it down first!

So, Teammate 1 is going to:

- Commit what they are working on
- Checkout to their local main branch
- Pull down the code from the main branch in Github to their local main branch
- Check back out to the branch they were working on
- Pull their local main branch into that branch
- Keep working!

![](../Images/GitHub-Flow-4.png)

### Starting A New Branch

Similarly, Teammate 2 now needs to get the new code in their local branch and start a new branch. You can see here in the diagram that they:

- Pull in the main branch from Github into their local main branch
- Checkout to a new branch

![](../Images/GitHub-Flow-5.png)

### The process repeats

And finally at the bottom of the diagram you can see how this process repeat when Teammate 1 finishes their work.

![](../Images/GitHub-Flow-6.png)