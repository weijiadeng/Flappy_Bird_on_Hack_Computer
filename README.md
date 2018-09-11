# Flappy Birds on Hack Computer

## About the game
This simple game allows the user to move a bird up and down, and try to dodge the upcoming
 water pipes as many as possible. When the game starts, a bird of 30 by 30 pixels is shown
in the mid-right area of the screen. 

The user controls the bird as the followings:

The up arrow key is used to move the bird up.If the user does not press any key, the bird 
moves down. The 'p' key is used to pause the game. A series of water pipes will move right 
after starting the game. You can try to dodge them and fly as far as possible.

## How to run
The vm file are compiled jack program files. You can load them through the vm emulator 
provided by the nand2tetris project. The URL is 
https://www.nand2tetris.org/software

After downloading the software of nand2tetris project, unzip the package, enter the tools
folder, and double clike VMEmulator.bat(Windows) or sh VMEmulator.sh(Unix like system). 
JRE is needed to run the VMEmulator.

Open the vm_code folder using VMEmulator:
![image](https://github.com/pcgsf22/image_folder/raw/master/flappy_bird/1.png)

Before running the program, the animate needs to be set "no animation", and the speed need
to be set fastest:
![image](https://github.com/pcgsf22/image_folder/raw/master/flappy_bird/2.png)

Press the start button:
![image](https://github.com/pcgsf22/image_folder/raw/master/flappy_bird/3.png)

And Enjoy the game!
![image](https://github.com/pcgsf22/image_folder/raw/master/flappy_bird/4.png)

## How to compile
In order to generate the vm code files from the jack source code, you may either use the 
official compiler also provided in the above package, or you may use a compiler implenmented
by myself:
https://github.com/pcgsf22/Jack_Compiler
