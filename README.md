FAH-Cli
=======

Script to interact with folding@home using telnet

Folding at home is a project with a lot of years that is maintained by the university of Stanford. More information about the project at http://folding.stanford.edu/English/HomePage

A many years ago, i was a usual contributor but then i stop for a long years. Now i return to help this cause and i have 3 machines folding being 2 of them 24h by 7d computing.
With that i feel the need of create a script to easily execute commands in all the machines and from the command line. This script its more useful when you want to add some entries on the crontab so you can give a break to your computer, or because some other things.

You can use too FAHControl with remote administration enable, but the passwords are send in plain text. With this script you can logon remotely on the machine with SSH, and access all the client control features without use X over SSH.

USAGE
=======

fah-cli [arguments] 
or 
./fah-cli [arguments] if you have not copied to one of folders maped on your PATH or you doens't have mapped the folder where the script its mapped.

For now, this only works with one argument, but i intend to add the ability to the script deal with as many arguments as possible.
Its tested with pause and unpause, to pause the computing and resume. No feedback its provided when it is successfull but if no errors occurs it is ok.


EXPECTED FEATURES
=======

Feedback
=====

Feedback when the command completes successfully and more feedback on errors.

Help
=====

Print a page with commands and examples and argument provided help.
