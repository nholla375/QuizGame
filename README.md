## README.md

# Quiz Game 🧠

A Python-based quiz application that asks the user a series of questions, checks answers, and keeps track of the score. The project uses object-oriented programming to separate question data, question logic, and quiz flow.

## Features

* Dynamically loads questions from a data source
* Uses object-oriented design (`Question` and `QuizBrain`)
* Tracks score and question number
* Interactive command-line gameplay
* Displays final results upon completion

## How It Works

1. Question data is loaded from `question_data`.
2. Each question is converted into a `Question` object.
3. The `QuizBrain` class manages question flow and scoring.
4. The quiz continues until there are no questions left.
5. The final score is displayed to the user.

## Project Structure

```
├── data.py
├── question_model.py
├── quiz_brain.py
└── main.py
```

## Requirements

* Python 3.x
* No external libraries required

## Running the Program

```bash
python main.py
```

## Learning Goals

This project was built to practice:

* Object-oriented programming
* Class interaction and data flow
* Loops and conditionals
* User input and scoring logic
* Modular code organization
