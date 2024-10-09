# hangman_game

# Overview: 
Hangman is a classic word-guessing game that challenges players to guess a hidden word by suggesting letters within a limited number of attempts. If a guessed letter is not part of the word, a part of a hangman figure is drawn. The objective is to reveal the word before the hangman is fully drawn.

# Game Components
1. Word Selection:
The game starts by selecting a word from a predefined list. This list can include various categories (e.g., animals, countries, programming terms).
The word is hidden from the player, who will try to guess it letter by letter.

3. User Input:
Players input letters to guess the hidden word. The input is typically restricted to single letters to streamline the guessing process.
The game can also provide feedback if the input is invalid (e.g., entering more than one letter or a non-alphabet character).

4. Game State Representation:
The game displays the current progress of the guessed word. For instance, if the word is "PYTHON," it will initially show "_ _ _ _ _ _".
Each time the player correctly guesses a letter, the displayed representation updates to reflect the revealed letters.
Attempts and Hangman Figure:

5. Players are given a limited number of incorrect guesses (commonly 6-7). Each incorrect guess results in a part of the hangman figure being drawn.
The hangman figure usually consists of:
Head
Body
Arms
Legs
The game continues until the player either guesses the word or exhausts all attempts, resulting in a completed hangman figure.

# Win/Lose Conditions:
The player wins by correctly guessing all the letters in the word before running out of attempts.
The player loses if the hangman figure is fully drawn before they can guess the word.

# Game Flow
Introduction:

The game begins with an introduction and instructions explaining how to play.
1. Word Selection:
A random word is selected from a list, and the length of the word is displayed as a series of underscores (e.g., "_ _ _ _ _").

2. Guessing Process:
The player is prompted to enter a letter.

3. After each guess:
If the letter is in the word, it is revealed in the correct positions (e.g., if the word is "PYTHON" and the player guesses "P," the display updates to "P _ _ _ _ _").
If the letter is not in the word, a part of the hangman figure is drawn, and the number of remaining attempts is decremented.

4. Displaying Progress:
The current state of the hangman figure and the guessed word (with correctly guessed letters displayed) are shown after each guess.
A list of previously guessed letters may also be displayed to help the player keep track.

# End of Game:
The game concludes when the player successfully guesses the word or exhausts all attempts.
A message is displayed to indicate whether the player won or lost, along with the correct word if they lost.
Variations and Enhancements

# Categories:
The game can be expanded to include categories, allowing players to choose a category before starting (e.g., sports, movies, geography).

1. Difficulty Levels:
Difficulty levels can be introduced by varying the number of allowed incorrect attempts or the complexity of the words.

2. Multiplayer Mode:
The game can be adapted for multiplayer, where players take turns guessing letters.

3. Graphical User Interface (GUI):
A graphical version of Hangman can be created to enhance user experience, displaying images, animations, and better visual representation of the hangman figure.

4. Scoring System:
A scoring system can be implemented to track players’ performance over multiple rounds, awarding points for correct guesses and deducting for incorrect ones.

# Conclusion
Hangman is an engaging word-guessing game that combines elements of strategy and luck. 
Its simple mechanics make it accessible to players of all ages, while the potential for variations and enhancements keeps the game fresh and exciting. 
Whether played on paper, in a classroom, or as a digital game, Hangman remains a beloved classic that fosters critical thinking and vocabulary skills.
