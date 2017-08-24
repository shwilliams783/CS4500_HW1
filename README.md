# CS4500_HW1
Homework 1 for CS4500 - Intro. Software Development

# Current Status
The page will load with proper placeholders for the results on the page. The variables are defined and initialized

# Assignment Document from the Course
CS 4500, Fall 2017
HW1: A pretty strange game

Imagine there is a 10 by 10 grid sketched out on a metal wall. You place a red magnetic marker in the lower left hand cell of the grid. Now you repeat the following:

1. Randomly choose a direction: up, down, left, or right. Each direction should be equally likely, over the long haul, to be chosen.  Call the direction D.

2. Randomly choose a number of steps, either 0, 1, or 2. Each of these should be equally likely over the long haul.  Call the number of steps N.

3. Try to move the red marker N steps in the D direction. If that move would take you off the grid, go back to step 1 without moving the marker. 

4. If that move leaves you on the grid, move to the new position. If the new position happens to be the upper right hand corner of the grid, then you are done with the game (you win!).

5. It is at least theoretically possible that this game could go on for a very long time. If you have done step one 1,000,000 times, stop the game before doing step one 1,000,001, and report that situation.  

You are to simulate this (pretty strange) game. The program that you use must run on the PC at the front of our classroom. You may use any programming language that you’d like, as long as you can deliver one of three things:

1. A URL where your program runs. (In other words, your simulation is web-based.)

2. A single executable file that I can download and run on the computer at the front of our classroom without any modifications on my part.

3.  A JavaScript program that I can copy and paste into the W3 JavaScript Tutorial system and execute that way.

Notice that I do not intend to compile anything. You deliver a URL , an executable file, or a JavaScript source file; and I execute. 

When your simulation finishes, it should print to the screen this information, appropriately labeled:

1. How many times was step 1 executed? Did the game finish because the marker got to the upper right, or because you ran out of steps?

2.  Keep track of how many times either of the markers landed in a particular cell (we’ll call that a “touch”).  A touch includes the starting cell, and wherever a move finishes. What was the maximum number of touches for any cell? What was the minimum number of times a cell was touched? What is the average number of touches to a grid cell? The minimum and maximum should be non-negative integers; the average should be a positive real. (Note: the minimum and maximum may occur on multiple cells in the grid; that’s fine.) 

This is an individual assignment. You may NOT work with anyone else on this assignment. You may NOT ask for help from anyone but your instructor. You may NOT hire someone else to do the program. You may NOT look for solutions to this problem on the Web. I hope I’m being clear that this is to be your own work, and no one else’s.

Documentation is central. Each file you submit should have your name, the date, and other helpful information as necessary.  Make sure your opening comment includes an explanation of what the code is trying to do.

Use “paragraphing” comments to break up code. Subprograms (such as functions and/or procedures) should include a comment telling the reader the purpose of the code and any assumptions inherent in the code. Any tricky parts of code should be commented to enhance human readers’ understanding of your intent, and the details of the implementation.

Again, your code has to run on the PC at the front of our classroom. 

Personally, I think a web-based solution will be the easiest choice. If your code runs in a browser, that makes things easy on you and easy on me. However, I don’t insist on it for this first assignment.

Your web-based program should run on at least one of the browsers available on the computer in front of our classroom, in the version that is running in front of our classroom. If your solution only works with one of those, you should alert me to which one.

You will have to turn in an RTF file containing all your source code. There will be a dropbox.

If you want to turn in an executable file, there will be a dropbox for that.

If you want me to run your program by visiting a website you set up, you have to give me the URL. There will be a dropbox for that.

If you want me to run your Javascript program in the W3school Javascript tutorial, you will need to put another copy of your RTF source code file into another dropbox.

All of these dropboxes are in the HW1 folder in DOCS & ASSIGNMENTS.

Be sure to get clarifications from the customer (your instructor…, me…) if necessary.

Keith

