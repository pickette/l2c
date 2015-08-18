# l2c -- Learn to Code
This repository contains resources for the coding cohort.

## Goals
I recognize that a variety of different goals exist within the group.  If you have not already, please communicate your specific goals to me so that we can try and achieve them (particularly if they are not reprsented below).  Here are some themes that have emerged so far:

+ A reasonable understanding about how enjoyable the activity of coding is and whether you'd like to continue learning more. 
+ A higher level of tech literacy and a better understanding of how startups work.
+ Being able to solve a paricular computer problem such as automating mundane tasks, scraping a website for data or making a website.
+ ...

We should collectively revisit goals in the future once we can gauge a longer term level of interest from people to make sure we are providing the right value to people who continue to be interested.

## Methodology

We'll begin with an in-person crash course overview of things. The outline for that workshop will be in a workshop0 folder (not there yet).  If there is interest in future workshops, outlines for them will also be in this repo.

One of the outcomes of the in-person workshop will be an introduction to a project management system called Jira. We will use this system to track the work we are doing.  Additional work an assigments will be communicated through this tool.  This will allow the majority of work to take place remotely and in a very similar style to how start ups work.

Ideally, I'd like to have a short once a week meeting via google hangout to allow people to quickly tell others what they're working on, whether they need help with anything and communicate any other issues they are having.  Also, for those who have time, I can do a bit of teaching remotely. If we can't find a mutually agreeable time, we may just need to do this more adhoc. The majority of communication should be through the slack channel and comments on code during code review, but it's still just nice sometimes to be able to talk rather than type about things.  


## Getting Started Instructions

+ Make a [github account](https://github.com/ "github")

  Github is a version control system and the primary way that we'll share code with each other.

+ Accept Slack invite, make an account and join the channel ( if you have not received an invite, let me know).

  Slack will be the primary way that we communicate with each other.

+ Install a good text editor. 

  If you think its highly likely that you'll be really into this, then it might be worth trying to learn a really powerful editor like Vim or Emacs.  Both have strong proponents.  I'd recommend Vim simply because its what I use and could help you with and the most compelling argument about which editor to use that i've heard is to use the one's your friends and co-workers use. On a mac this should already be installed and can be opened from the terminal with ```vim```  

  [a game to learn vim](http://vim-adventures.com/)

  [a tutorial that i haven't tried, google might produce other better ones, not sure](http://www.openvim.com/)

  However, that being said, most of you probably shouldn't dive in to using vim.  If you think the chances are relatively low that you'll end up wanting to be a developer or otherwise want to get super awesome at text manipluation, then you'd be better off with an editor like [sublime](http://www.sublimetext.com/). 

  There are many choices, so if you don't like something that you try, its totally fine to try another.

+ Ensure that you have Python 2.7.9 as well as pip installed.
  + Python version can be checked by opening the terminal and running ```python --version```
  + pip can be check similarly by running ```pip --version```
  + There is a good chance your mac came installed with python, in which case the above will work, if not: follow instructions [here](http://docs.python-guide.org/en/latest/starting/install/osx/) 

## Assignment 0
  Submit a Pull Request to this Repository that adds your name to the roster.txt file

  First, fork the repository by clicking on the fork button in the upper right hand side of this screen. Then clone your fork with:
``` 
  git clone https://github.com/[your_user_name]/l2c.git
```
  Then in the directory on your local machine, edit the roster.txt file to include your name. Then in the command line:
```
  git add .
  git commit
```
Then hit i to go into insert mode (this will give you a taste of vim to see whether or not you want to dive into it) and type a message.  This should simply describe whatever change you are making. You can save and quit this file by typing ```:wq```  After this you can push your changes back with
```
  git push
```
If all has gone well, you can go back to the web page for this repo that is under my name and not your fork. And click on the green button with arrows in it.  This will bring up a pull request form and you can provide any additional comments. Fill out the form to submit a pull request.  In the comments, tag me with @nathanlubchenco so that I'll get emailed about it.  Then I can review it and merge the change in.

If you get stuck, please ask for help from myself or someone else that has succesfully done this.  The list of people who have succeeded will be apparent from the contents of the roster.txt file.

## Misc

Don't worry if you don't understand all of this yet, we'll talk more about what's going on here in the future. But if you want to learn more now, google is your friend as well as [stack overlow](http://stackoverflow.com/). Also please ask questions and clarifications, if you have a question, there is an excellent chance that someone else would benefit from hearing the answer.
