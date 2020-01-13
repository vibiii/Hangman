Hangman game

This repository contains the files used to create the hangman game :
Hangman.ipynb is the main file containing the code of the game
The .JPG files are files that are used and called in the code of the game

Description of the game :

The program will select a random word that will respect the following requirements :
- english language 
- min 5 letters
- be part of the dictionary
- be composed of letters only (no punctuation mark)

Once the game starts, the player is shown the number of letters to find in the following format ('_ _ _ _') and asked to guess a letter.
If the player enter any other thing that ONE LETTER (ex : 2 letters, a figure,...), a message will inform him that he did not make an authorized choice and he will be requested to make a new choice.
The choice of the player will not be case sensitive, either he enters a letter in uppercase or lowercase the game will run and if the letter choosen is part of the word, the player will win the round.

If the player picked a letter that is in the word to find he will be shown :
- a message informing him that he guessed a correct word
- an updated version of the word to find with the letters found so far in the following format ('_ E _ _')

If the player picked a wrong letter he will be shown an updated version of the gallows that reflects his current situation.
The gallows will be composed of 6 different steps :
- head
- body
- left arm
- right arm
- lef leg
- right leg

The game will run until either the player wins (finds the word before he is hung) or loose (is hung)

At the end of the game :
- if the player wins he will be shown a congratulation message
- if he losses he will be shown a message and the word that needed to be found.
 
