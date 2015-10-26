gt-cs6250
=========

## CS6250

Project codes for CS6250(Computer Networking) of Georgia Tech for Spring 2014. All the videos are from gtnoise.net/classes/cs6250/spring2014.

moqiguzhu(moqiguzhu@gmail.com)
Forked from https://github.com/udacity/gt-cs6250.git

I have not attended any plan of Georgia Tech, all the videos are placed at Youtube.com publicly.

## git configuration
- clone the original CS6250 repo
$ git clone https://github.com/udacity/gt-cs6250.git

- create a repo called CS6250 at github.com as usual

- configure user-email and user-name on local repo

- connect local repo and remote repo
$ git remote set-url git@github.com:moqiguzhu/CS6250.git
$ or git remote add origin git@github.com:moqiguzhu/CS6250.git
pay attention to that origin is just a name for remote repo, myorigin or other names will also be fine. you can use the following command to remove the current connection to remote repo.
$ git remote rm origin

- next, we need to deal with ssh keys
$ cd ~/.ssh
$ ssh-keygen
add the generated ssh key to github account
$ ssh -T git@github.com
$ git push -u origin master



## Assignment 1
mininet setup
 
