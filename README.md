**Number Guessing Game (Python)**

This is a simple Python-based Number Guessing Game where the computer randomly selects a number, and the player tries to guess it. After each guess, the program gives feedback to help the user reach the correct answer.

This project was created as part of my Python assignment to practice:

--Basic Python logic

--Using loops

--Conditional statements

--User input handling

--Git & GitHub workflow

 *Features*

✔ Random number is generated automatically

✔ User receives hints (Too High / Too Low)

✔ Counts number of attempts

✔ Validates incorrect inputs

✔ Simple and beginner-friendly logic


 *How the Game Works*

--The program chooses a random secret number between 1 and 100.

--The user enters a guess.

--The program checks:

   If the guess is too high

   If the guess is too low

   If the guess is correct

--The game continues until the correct number is guessed.

--Finally, the program prints how many attempts the user took.

 *Code Explanation (Simple Terms)*
 
1. Importing Random Module
   
import random


We use the random module to generate the secret number.

2. Generating a Random Number
   
secret_number = random.randint(1, 100)


This picks a number between 1 and 100 for the user to guess.

3. Loop for User Attempts
   
while True:


The loop keeps running until the player guesses correctly.

4. Taking User Input
   
guess = int(input("Enter your guess: "))


The user types their guess, and it’s converted to an integer.

5. Checking the Guess
   
if guess < secret_number:

    print("Too low!")
    
elif guess > secret_number:

    print("Too high!")
    
else:

    print("Correct!")
    
    break


If guess is smaller → tell user Too low

If guess is bigger → tell user Too high

If equal → game ends

6. Counting Attempts
attempts += 1


This increases the attempt count each time the user guesses.

 *Running the Game*

Run this command in your terminal:

python game.py


Make sure you're inside your project folder.

📁 Project Structure

Number_gussing_game/

│

├── game.py

└── README.md

What I Learned

How loops work in Python

How to compare values and make decisions

How to use the random module

How version control (Git & GitHub) works

How to write clean commit messages and create a README
