PYTHON ADVENTURE GAME 

Project Overview 

This project is a text-based treasure-hunting adventure game. The 
player is an explorer searching for a legendary treasure in an ancient land. The player chooses either a dark forest or a mysterious cave, then makes decisions that lead to winning or losing the adventure. 

Files 
adventure_game.py - Main interactive command-line Python game. 
index.html        
adventure. - Optional browser interface for playing the same 
Python Concepts Used - Variables: store the player's name and choices. - Functions: separate the game into start_game, forest_path, 
cave_path, 
ask_choice, and play_game. - Conditionals: determine what happens after each decision. - Loops: validate player input and allow the game to restart. - Lists/sets: hold valid player choices for each question. - Input/output: collect choices with input() and display story text with 
print(). 

Game Flow 
1. The game asks for the explorer's name. 
2. The player chooses the forest or cave path. 
3. The player makes further decisions in that location. 
4. The game ends in a win or loss. 
5. The player can replay after every completed adventure. 

Winning Paths 
Forest: Follow the river -> Search beneath the bridge 
Cave: Light a torch -> Read the symbols 

GitHub Copilot Assistance 
GitHub Copilot helped structure the game into small functions, add reliable input validation, and organize replay logic. This made the code easier to read, test, and modify while using the required Python fundamentals. 

Enhancements - Invalid choices are handled without ending the game. - The player can restart after a win or loss. - The optional browser interface provides button-based choices while preserving the same story branches as the Python CLI game. 
