# Digital Timer
 
## Part A. Solder your LCD panel
![Image of SolderLCD](https://github.com/zicongwei/IDD-Fa19-Lab2/blob/master/sold.jpeg)

## Part B. Writing to the LCD
 
**a. What voltage level do you need to power your display?**    
5v

**b. What voltage level do you need to power the display backlight?**  
3.3v
   
**c. What was one mistake you made when wiring up the display? How did you fix it?**  
1) At first I forgot to connect the breadboard vertically, so I used 4 jumpers to wire them up.
2) My LCD is broken, so it could not show "Hello World". By simply using another LCD without changing any wire, the whole system works. 

**d. What line of code do you need to change to make it flash your name instead of "Hello World"?**    
`lcd.print("hello, world!");` to `lcd.print("hello, Irene!");`

**e. Include a copy of your Lowly Multimeter code in your lab write-up.**  
[link to Lowly Multimer code!](https://github.com/zicongwei/IDD-Fa19-Lab2/blob/master/voltmeter.ino)

## Part C. Using a time-based digital sensor

**Upload a video of your working rotary encoder here.**  

[rotary encoder video!](https://youtu.be/nD4gTdD3ntg)

## Part D. Make your Arduino sing!

**a. How would you change the code to make the song play twice as fast?**   
change the noteDuration  
`int noteDuration = 1000 / noteDurations[thisNote]/2;`
  
**b. What song is playing?**  
Star Wars

## Part E. Make your own timer

**a. Make a short video showing how your timer works, and what happens when time is up!**  
[My Timer!](https://youtu.be/-ktWo4iBLG8)

** Pre Lab **
1. Use a timer to time people’s workout times. 
2. Timer for cooking, when the food is ready, it will sings.
3. Pressing the button in a certain time, as fast as possible, to light up more LEDs.
4. A game: In a certain time, remember LEDs lightening sequence, and try to copy the order by pressing the buttons.
5. Two player press buttons, like a running game, and measure the time.
6. A CD player shuffeling songs,  people can switch songs in a selected times.
7. An sleep alarm with soft music, set up before people go to bed.
8. Timer for counting down the time wait for taking elevator and taking stairs.
9. Alarm the teacher's time for the end of class.
10. Game: Trying to remember a memlody of a song in a short time. 

