# Wordle Game

![Contributors](https://img.shields.io/github/contributors/nascho/react-calculator?style=plastic) ![Forks](https://img.shields.io/github/forks/nascho/react-calculator) ![Stars](https://img.shields.io/github/stars/nascho/react-calculator) ![Issues](https://img.shields.io/github/issues/nascho/react-calculator)


## Description 

This repository is for being used for a Wordle Game using Python and PyGame and is part of a small out of hours project while attending Generation UK&I's AWS Re/Start programme.

It is a fully functioning application, please feel free to use it.


__Techologies Used__ 

As part of the project the technologies we settled on were:

![Python](https://img.shields.io/badge/-Python-blue?style=flat-square&logo=python&logoColor=white) ![Pygame](https://img.shields.io/badge/-Pygame-green?style=flat-square&logo=python&logoColor=white)


## Installation & Running Project

Please click the link below to copy the pathway for cloning the project:

```sh
   git clone https://github.com/nascho/wordle_game.git
```

Once cloned please install the PyGame package:

```sh
    pip install pygame
```

For Windows in the terminal run the following command to start the game:

```sh
    python main.py
```

For MacOS in the terminal run the following command to start the game:

```sh
    python3 main.py
```

When the program starts a model will appear for you to interact with the game.

## Game Rules

Wordle is a simple word-guessing game where players try to guess a secret 5-letter word within six attempts. Here's how the game works:

#### 1. **Objective**
The goal is to guess the secret 5-letter word within six tries.

#### 2. **How to Play**
- Each guess must be a valid 5-letter word.
- After each guess, the letters in the guessed word will be marked in different colors to give feedback on how close your guess was to the secret word.

#### 3. **Feedback**
- **Green**: The letter is in the correct position in the word.
- **Yellow**: The letter is in the word but in the wrong position.
- **Gray**: The letter is not in the word at all.

#### 4. **Rules**
- You have six attempts to guess the word.
- Every guess must be a valid 5-letter word.
- Letters can appear more than once in the word, but feedback applies to each occurrence separately.
- The game ends when either the player guesses the word or runs out of guesses.

#### 5. **Winning**
- You win the game if you guess the word within six tries.

Good luck!
