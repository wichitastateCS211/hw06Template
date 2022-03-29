# Hail Caesar *(shift)*!
A Caesar shift is one of the oldest forms of encryption. It was originally implemented using two strips of paper with the alphabet written on them. One of the strips was then shifted a certain number of spaces over. For example, a shift of 3 would change the letter 'A' -> 'D', 'B' -> 'E', ..., 'Z' -> 'C'. As can be seen, the alphabet wraps around.

This assignment will allow the user to enter a message, we will then encode it by shifting it 4 characters over and decode it again.

## Requirements
- Declare 2 functions, one to encode and the other to decode the message.
  - **IMPORTANT:** Any circumvention of these functions for the sake of "correct output" will result in a grade of 0 for this assignment.
- Declare the necessary constants in your `main()` function.
- When the user is done typing the message, they will hit the Enter key. That keystroke is **not** to be saved to the array.

## Sample Run
Please enter a message: zip zap zooey

ZIP ZAP ZOOEY  
DMT DET DSSIC  
ZIP ZAP ZOOEY

## Hints
- Recall that a character can be thought of as a small integer. We can use this to our advantage. https://asciitable.com
- For simple encryptions, decoding is simply reversing the encoding process.
  - Encoding will likely be a mix of the actual encode process and a character control process.
- The requirement concerning the Enter key can be taken care of for you by your input method.

## Reminders
- Name your file *wsuid*\_hw06.cpp
- You are required to place a comment block at the top of the file. Refer to the Coding Guidelines
handout.
