# 3D_Maze
The goal of this project is to create a game in 3D using raycasting for alx Final project using c programming language.

![maze_gif](https://github.com/ukcharlies/3D_Maze/assets/111245934/a7c78b9e-34bf-436d-81d2-406563354c1f)

* The objective of the ALX Final project is to develop a 3D game using raycasting, implemented in the C programming language.

* The maze for this project was created using C and the SDL2 library. The development process took place on Ubuntu 14.04 LTS, utilizing the gcc compiler version 4.8.4.


* This game is compatible with Mac OS X and Linux/Ubuntu operating systems. The raycasting technique is employed to achieve a visually immersive 3D representation of the maze.
# About SDL2
* SDL2, short for Simple DirectMedia Layer, is a versatile development library that offers cross-platform compatibility. Its purpose is to provide developers with direct access to audio, keyboard, mouse, joystick, and graphics hardware using OpenGL and Direct3D. It serves as a crucial component for various applications, including video playback software, emulators, and acclaimed games such as Valve's renowned catalog and numerous titles featured in the Humble Bundle. For additional details about SDL2, please refer to the relevant resources available.
# Requirements to Play
* Linux/ubuntu or Macos
* SDL2 and its sdl_image
# Installation
* Download the installation script named "install_SDL2.sh" to your desired location, such as the "Downloads" folder.
* Open the terminal on your Ubuntu system.
* Change your working directory to the location where you downloaded the installation script. For example:
* Verify that the "install_SDL2.sh" script is present in the current directory
* Make the script executable by running the following command
* Run the installation script with root privileges using the following command
# Play the game
* clone the [GitHub repository](https://github.com/ukcharlies/3D_Maze)
* Compile all .c files in the maze directory using:
gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm $(sdl2-config --cflags --libs) -lSDL_image -o maze
* Execute ./mazea and play the game.
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

# Controls
W or up arrow key - Moving forward S or down arrow - Moving backwards left arrow key - to rotate the player in a counter-clockwise direction right arrow key - to rotate the player in the clockwise direction
# Flow Chart
![flowchart](https://github.com/ukcharlies/3D_Maze/assets/111245934/586b7ee6-aa9a-4df7-9c14-01f2f3bed000)
# Project Demo
![project_demo](https://github.com/ukcharlies/3D_Maze/assets/111245934/3936f284-11b2-4bb4-86a8-10b6c05422ba)

# Author 
* Ukachi Charles [github](https://github.com/ukcharlies) [linkedln](https://www.linkedin.com/in/chuka-ukachi-70b525262)

