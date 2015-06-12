# snake_py32
snake game coded in python3.2 (and pygame)

This is a fairly simple program that I've coded in order to learn how to use a GUI.
There are basically five python files:

1. snake_main_menu.py
The first file is self-explained by it's title. This is the script where the main loop of the game is.
It basically consists on a list of options (play, settings, exit).

2. snake_core.py
This is the actual snake game, it is called by the main menu when the user clicks the "play" button.

3. settings_menu.py
The settings menu, called when the user clicks the "settings" button. Only one option can be changed for now:
the snake movement speed.

4. settings.py
This file is actually a variable storage. It contains a few global variables that are used by the
other python scripts. It could be replaced by a generic text file (though that would demand some changes in the
other scripts as well).

5. setup_snake.py
The last one is a cx_freeze script that can be used to generate windows 32 bit binaries.
