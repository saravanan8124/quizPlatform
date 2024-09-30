**OverView**
-   Save high scores in Local Storage
-   Create a progress bar
-   Create a spinning loader icon
-   Dynamically generate HTML in JavaScript
-   Fetch trivia questions from Open Trivia DB API

-   JavaScript - Array Functions (splice, map, sort), Local Storage, Fetch API
-   ES6 JavaScript Features - Arrow Functions, the Spread Operator, Const and Let, Template Literals
-   CSS - Flexbox, Animtations, and REM units



## 1. Create and Style the Home Page

 To create the home page along with a good chunk of the necessary CSS. The home page will consist of a few links for the Game and High Scores pages. Also create helper CSS classes for Flexbox, buttons, and hiding elements.


## 2. Create and Style the Game Page

Create the Game Page and display static question and answer information. Eventually,load questions from an API, but for now,  hard code one question so to establish styling.

## 3. Display Hard Coded Question and Answers

Load questions from a hard coded array and iterate through available questions as the user answers them. use custom data attributes, the ES6 spread operator, and JavaScript arrow functions.

## 4. Display Feedback for Correct/Incorrect Answers

Check the user's answer for correctness and display feedback to the user before loading the next question.


## 5. Create Head's Up Display (HUD)

Create a Heads Up Display (HUD) for our quiz app. This will display the user's score and current question number.


## 6. Create a Progress Bar

Take our HUD one step further by creating a visual progress bar to track the user's progress through the questions.

## 7. Create and Style the End Page

Create our End page where we will display the user's achieved score. This screen will provide a form for saving the score and links for playing again or going home.

## 8. Save High Scores in Local Storage

Save and maintain a high scores array in Local Storage. To do this, need to JSON.stringify() and JSON.parse() to convert our high score array to a string and visa versa.

## 9. Load and Display High Scores from Local Storage

Create our High Scores page. We will have to load the high scores from Local Storage, iterate through them, and display them on the screen.

## 10. Fetch API to Load Questions From Local JSON File

Move our sample questions from a hard coded array to an external .json file. This will help clean up our Game.js file and set ourselves up to request questions from an API in the next video.

## 11. Fetch API to Load Questions from Open Trivia API

Use Fetch to request a list of questions from the Open Trivia DB API.

## 12. Create a Spinning Loader

Create a simple spinning loader in CSS that will be displayed until we are finished requesting/loading questions from the API.
