# debug_workshop

Preperation
------------

Create a new virtualenv called "debug_workshop" like so:
$ mkvirtualenv debug_workshop

activate the new virtualenv.

Create a new folder and "cd" into this folder, then clone this repository to the newly created folder:
$ git clone https://github.com/ticOlof/debug_workshop.git

Open the newly cloned repo in PyCharm 5.0 using the File->Open menu option.

Set the project interpeter to use your newly created virtualenv.
From PyCharm, with the project opened, go:

File -> Settings -> Project: debug_workshop -> Project Interpeter

Press the little cog in the top-right corner and choose "Add local"

Navigate to where you created your virtualenv (for example /home/admin/virtualenvs/), expand the debug_workshop and look in the "bin" folder. In here, locate the Python2.7 shortcut and appoint that file to the interpeter. 

Press Apply and OK

Await PyCharm to update your project, and if all went well, you should be able to run the project using PyCharms runconfiguration (the little green arrow or pressing Shift+F10)

To debugg, press the little bug or Shitf+F9

Fix the code and finish the game, 

Good luck!











