bash_ext
========

Because my default ubuntu .bashrc is not good enough.

installation
============

$ cd ~
$ git clone https://github.com/neblackburn/bash_ext.git

This will create a directory called bash_ext at ~.

Now:

$ vi ~/.bashrc

at the bottom add:

if [ -f ~/bash_ext/.bash_ext ]; then
. ~/bash_ext/.bash_ext
fi

Now you can tweak/update your .bash_ext file and not worry about messing up your .bashrc

More to come like alias' and such.
