

mlb
######

|
|




Goals
~~~~~~~~~~~~~~~~~~~
* create branch
* work on branch
* merge branch
* multiple coexist branches
* remove branch
* never del on github, del on your computer 



|
|



::

  git checkout -b branch_1 is the same thing as:
  git branch branch_1    (create)
  git checkout branch_1  (switch to)


  # switch to a branch: 
  git checkout branch_2

  git checkout main (not master anymore!)



|




::

  D:\GITHUB_Repos\mlb>git branch  # i only have one branch right now 
  * main  

  D:\GITHUB_Repos\mlb>git branch branch_1
  D:\GITHUB_Repos\mlb>
  D:\GITHUB_Repos\mlb>git branch   # now i have a new one... 
    branch_1
  * main

  note:  i actually like using:  git branch --list  (vs git branch)



  D:\GITHUB_Repos\mlb>git checkout -b branch_2
  Switched to a new branch 'branch_2'

  D:\GITHUB_Repos\mlb>git branch --list
    branch_1
  * branch_2
    main
  
  Thats great but has it been pushed up ? 

  Try to push and you will see this:

  fatal: The current branch branch_2 has no upstream branch.
  
  To push the current branch and set the remote as upstream, use
     git push --set-upstream origin branch_2



















|



:Author: T 
:Date: Nov 2020



|
|
|
