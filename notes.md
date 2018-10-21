This tutorial will be composed of two parts. The first will focus on git as a version control system, and it's utility in tracking and versioning files for efficient workflows. The second part will focus on Github, which is a user interface and development platform. 

git itself was originally developed to host and version the Linux kernel, as designed by Linus Torvalds (a Finn). 

I think the stereotypical git user is something akin to this person. The idea is that git is a tool only utilized by developers. I don't think that's the case. It's pretty easy to use once you invest a bit of time, and the payoffs are substantial. 

So I would argue that when you think of git users, perhaps this is a more accurate picture. It's a great thing about open source software and tools. Everyone has access, and so everyone can use. 

Version control itself is a simple concept. A version control system is such that the user can track and recall different versions of files. 

I think many of us have run into this situation, where we share a document/manuscript/piece of code with a collaborator, and it comes back to us with edits. To incorporate those edits, we create a new file, which contains much of the same information as the previous file, but perhaps with an additional number, or letter, or note. This is not only a waste of space, it is a needless complication that can cause you to misplace or confuse different versions, and doesn't allow you to linearly follow previous edits/thoughts/etc.

If you ask git developers how git works, they give this diagram, which shows that same file as the previous slide, but maintaining the same name, and being accessed by different computers. Each version represents a snapshot in time, and the previous state of the file (or files, as repositories typically contain multiple files that are all versioned together). 

Even if you are developing both by yourself and on a single machine, git can be incredibly useful. This shows the progress of one of my current projects, where the line represents time, and each point represents a snapshot of the files at that time. Each dot, as I'll go over in a bit is a commit. For this project, I had an idea to incorporate a null model to address some coauthor concerns. In order to do this, I created what is called a branch. This is a virtual copy of the repository, where you can hack away some additional functionality. The idea being that if the results were garbage, I could simply delete the branch, and the master branch is still intact and unchanged. In this case, the incorporation of the null model was useful, and I incorporated the results into the manuscript and code, and merged this branch back into the master branch. 

So each one of those dots in that time series represents a snapshot, and git allows you to provide a message containing the details of what has changed. It is essentially the metadata at that given time, showing what was added or changed. Super useful. Unless it's not. But this slide is put in basically to emphasize the importance of informative commit messages. 

It's also important to note at this point, before I showcase the utility of git independent of the web platform Github/Bitbucket/etc. that git isn't simply a command line tool. There are a large number of GUIs available, and RStudio, which many of us use I imagine, has a nice git integration. 

So at this point, I'd like to switch over to the command line to simply show you how git works on your local machine. I'll go over some of the jargon that will give you pause and make you wonder if learning git is more trouble than it's worth (which it's not).

And to do this, I'd like to use the folder containing all the files necessary to create this presentation. My speaking notes, which I am typing right now (and probably are more informative than the words I actually spoke during the tutorial), etc. 

So I've been using git to version the changes in this presentation. First, we cd, then we can status, log, ....


((live demo))

Now I'll switch gears and talk about Github, which allows you to utilize the same versioning utilities as git, but to do so with collaborator input, allows issue tracking, and public hosting so that people see your science. 

So just like the stereotype of the git user as a techie, the stereotype of a Github user is pretty much the same. And this one holds a bit more water, as the top repositories often belong to large tech companies. However, companies like Google and Facebook also have research tools which are openly available that are of great use to ecologists (Facebook's Prophet for time series forecasting, Google earth engine and associated tools, etc.)

So maybe I've convinced you that using git for version control is a useful thing. If so, good. Now I'll attempt to make a case for Github as a dev platform. The real strength of Github, in my opinion, is that it's popular, allows multiple users to collaborate on a project, allows issue tracking (which I'll show you in a minute), assignment of tasks, and progress tracking. I also think it's important to distinguish things hosted on Github from code and data deposited for a manuscript. Github is the current flavor, but there are other services. In this sense, Github is not permanent. Without external integration, Github repos are not citable. They can be deleted at any time. Changed. Made private. Use figshare/dryad/etc.

Alright. So now I'll switch over to the web interface, and show you how Github works, still using the repository I have been (the repository that is versioned and is only on my local machine containing the slides and stuff for this tutorial). 

In the process, we'll go over some more jargon and hopefully start to get familiar with how the local machine can interface with the web service, as well as show you the features of Github itself. 

((live demo))




Lastly, there are some really great online resources if you are more serious about learning about git and Github. Some of them are listed here. Thank you for your time. 

