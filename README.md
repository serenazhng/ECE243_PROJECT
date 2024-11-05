# ECE243_PROJECT
Memory Game coded using C for implementation on a VGA using an FPGA board for my final project for ECE243

MEMORY MANIA
Description 

The aim of the game is to recall a sequence of colors outputted to the screen, within a time limit. The higher the number of colors you get correct (by entering the right color in the correct order), the higher score you will get. 

Instructions 

How to play: 

1. Main screen: Press Key0 to start a new game. If Key0 is not pressed within 3 seconds, the game starts automatically. Background music will play while on the Main Screen. 

2. Outputting sequence: Now, a sequence of colored circles will be outputted to the screen, in the correct order. No user input required here, just try and remember the sequence! 

3. Enter sequence:  

  a. Using the keyboard and the keymap displayed on the screen, enter the color you wish to select using the corresponding key on the PS2 keyboard, and submit that selection using Key0. 

  b. You may wish to undo a selection at any time using Key1. 

  c. There is a time limit, keep an eye on the timer displayed on the hex displays.  

  d. The game will automatically move forward with the answer stage if either the timer is complete, or all the colors are submitted. 

4. Answer sequence: The correct answer, your selection, and your score will be displayed onto the screen. The score is calculated based on the number of circles you got right. 

5. The game returns to the home screen after 15 seconds, after which you may choose to play again. 
