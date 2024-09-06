# DinoDodge
This is an enhanced remake of classic Google dino game with added design features, combining C++ with FPGA and hardware peripherals. 

It is an endless runner game in which the player must control a dinosaur character to avoid cacti and pterodactyl obstacles. The player begins the game with three lives, and loses a life each time the dinosaur collides with an obstacle. The objective of the game is to survive for the longest time possible. The game requires access to a NIOS II system, PS/2 keyboard, and audio speakers.

The player begins the game with three lives. The number of lives remaining during a game is represented on the DE1-SoC LEDs. The LED display is updated upon collision. The elapsed time during a game is displayed on the DE1-SoC HEX display. The time is updated every second. The game uses the following keyboard controls:
LEFT ALT – duck low to avoid pterodactyl obstacles in the air
SPACEBAR – jump to avoid cacti obstacles on the ground
HOLD SPACEBAR – activate hyperjump; press any other key to cancel
ENTER – navigate the transition screens between games

Dino Dodge supports graphics for both day and night mode. Toggle SW[0] on the DE1-SoC to change the background theme. Use speakers to listen to brief audio clips during game state transitions.
