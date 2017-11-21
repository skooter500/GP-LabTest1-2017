# DT508 Game Programming Lab Test 1 2017


## Rules of the test

- This is an open book test. You can use any of your own sketches, any of the examples from the [course website](https://github.com/skooter500/GP-2017-2018) or the [Processing reference](https://processing.org/reference/) during the test.
- No conferring or collaboration.
- No use of Google, Facebook or any any other web resources permitted.

## Useful references:

- [The Processing reference](https://processing.org/reference/)
- [The course website](https://github.com/skooter500/GP-2017-2018)
- [Google Classroom](http://classroom.google.com)

## Instructions

Here is a video of the sketch you will be making for the test:

[![YouTube](http://img.youtube.com/vi/nsCe1NBQW8Q/0.jpg)](https://www.youtube.com/watch?v=nsCe1NBQW8Q)

- Start with a blank sketch and save it as D111111_Bryan_Duggan. *Replace D111111 with your student number and Bryan_Duggan with your own name*

What is happening:

- The key and player spawn at random positions in the bottom half of the screen
- The player character is controlled with the up, down, left and right keys
- The star positions are stored in 2 arrays of floats (one for x and one for y). You should give these initial values in the setup function and draw them in the draw function.
- The door of the house is drawn in red initially. The player should collect the key and then go to the door.
- When the player has the key and arrives at the door it should be drawn in black to indicate that it is open and the key should reappear randomly in the bottom half of the screen
- You might want to use the Processing [dist](https://processing.org/reference/dist_.html) function to check if the player picks up the key or arrives at the door. This calculates the distance between two points and you can check if the distance is < 20
- A message is shown in the top left of the screen that indicates what the player should do next. Use the [text](https://processing.org/reference/text_.html) function for this.
- To get full marks in the test, you should use variables and functions in your solution
- When you are finished, zip your sketch folder up and rename the zip file to be D111111_Bryan_Duggan. *Replace D111111 with your student number and Bryan_Duggan with your own name*.
 - Enrole in the module Game Programming on Google Classroom using the code s3n06gw and submit your zip file through the assignment Game Programming Lab Test 1.
 - I suggest you email a copy of the assignment to me too at bryan.duggan@dit.ie to be safe

## Marking Scheme

| Description | Marks |
|--------------|---------|
| Drawing the house and the ground | 10 |
| Drawing and moving the player | 20 |
| Drawing the stars | 15 |
| Drawing the key at a random position | 15 |
| Collecting the key | 20 |
| Opening the door | 20 |
