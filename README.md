Git Collaboration 1
===================

## Learning Objectives

* Use git from the command line to stage, commit and push local changes to a remote GitHub repository
* Explain the purpose of the commands git status and git log.
* Collaborate with a partner using git and GitHub

## Introduction

Git is a tool we use to manage changes in our code projects.

## Exercise 1

Decide who's Bob and who's Alice.

Alice, on your computer:

* Create a new directory called 'introductions'
* Initialise the directory as a new git repository

Try out `git status` and see what it says — it's usually useful information. If it says 'Not a git repository' then something is wrong.

## Exercise 2

Alice, on your computer:

* Create a new file called `index.html` in the directory called 'introductions'
* Ask your pair partner their name
* Add the following to it, replacing `NAME` with their name:

  ```html
  <h1>Hello NAME!</h1>
  ```

* Stage and commit this change.

Try out `git log`. You should see your commit there.

## Exercise 3

Alice, on your computer:

* Create a new GitHub repository called 'introductions'
* Set up your local git repository to point towards the GitHub repository
* Push your local changes to the Github repository
* Add your partner as a collaborator on the Github repository

Check out the repository page on Github. You should see your file there.

## Exercise 4

Bob, on your computer:

* Clone (don't fork) your pair partner's 'introductions' repository
* Open the `index.html` file in your browser/Live Server to check it works
* Add a new html element to 'index.html' saying hello back
* Stage, commit and push your changes

Check back on that repository page — do you see your new changes on Github?

## Exercise 5

Bob, on your computer:

* Open the repository on Github and find the list of commits
* You should see two commits with your photos
* You should be able to click the photos and see your Github profile

Here is an example of how it should be:

![](./images/commit.png)


## Exercise 6

Both, on your respective computers:

* Set up your global git config to use:
  * Your real name
  * The email address you use with GitHub

Here is how you check it is set up correctly:

```bash
$ git config --global --get-regexp "user"
user.name edward
user.email edward@boolean.co.uk
```

## Exercise 7

Imagine it is a fresh new day, and you have a new person to pair with: Ada Lovelace.

We want to pick up from where we left off, but without interfering with Alice's repository. To do this, we create a new repository with the same code.

Either one of you, on your computer:

* Create a new repository on Github called 'introductions-2'
* Change your local repository remote to point to your new 'introductions-2' repository
* Write a new introduction to Ada
* Stage, commit and push your changes

Ada's introduction should now be on Github!

## Exercise 8

Using git involves learning a lot of strange commands with weird names.

How can we learn about commands like this? List some techniques:

* git recommendattion
* combinating symbols into words

Getting good at finding out information like this will help you become a better software engineer. Each additional technique you learn might save you days or weeks of time in the long run.
