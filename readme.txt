RazorCade theme

Changes:
Version 1.0

---------------------------------------

There are 38 systems themed if you count the RetroPie settings. The systems themed are

RetroPie
Sega Genesis 32X
Super Nintendo Entertainment System
Sega Genesis
Sega Master System
Nintendo Entertainment System
Multiple Arcade Machine Emulator (MAME)

---------------------------------------

Installation

Copy the contents of the 'themes' folder to the 'themes' folder of EmulationStation
Example: '/etc/emulationstation/themes' for the Raspberry Pi

You must at minimum copy the 'nbba theme' folder to themes. The two alternate layouts reference all of its resources from the main theme to cut down on disk usage and files.

Before the next step make sure to make a backup copy of the RetroPie 'gamelist.xml' file if you wish to revert the changes back. I have provided the default 'gamelist.xml' file my Raspberry Pi generated. Copy the contents of the 'gamelists' folder to the 'gamelists' folder of emulationstation.
Example: '/home/pi/.emulationstation/gamelists'

Copy the contents of the 'downloaded_images' folder to the 'downloaded_images' folder of EmulationStation.
Example: '/home/pi/.emulationstation/downloaded_images'

Copy the contents of the 'retropiemenu' folder to the 'retropiemenu' folder of RetroPie.
Example: '/home/pi/RetroPie/retropiemenu'

nbba theme - This theme layout will display the image referenced in the gamelist.xml as large as possible to take up the left half of the screen. A list of games is on the right with a few details listed about the game below the image.

nbba theme es - This theme layout keeps the default layout which is provided with EmulationStation.

nbba theme ns - This theme layout is similar to the nbba theme but gets rid of the list of games on the right for a single selection at the top. The image that is referenced in the gamelist.xml then expands to the maximum size of the space left.

