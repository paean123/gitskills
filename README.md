# gitskills

How to establish the connection between the local computer and Github?

1.
establish the SSH Key:
$ ssh-keygen -t rsa -C "paean123@126.com"
then you should open a file named id_rsa.pub in the .ssh, copy all of the words into Github/settings/SSH and GPG keys.
2.
pwd: make sure which directory you chooose to clone the Git
3.
$ git clone git@github.com:paean123/gitskills.git