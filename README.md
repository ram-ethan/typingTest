Typing Test - Readme
This project is a simple typing test web application built using HTML, CSS, and JavaScript.

Features:

Displays a random sentence from a predefined list.
User types the displayed sentence in the provided text area.
Calculates typing speed in words per minute (WPM) upon clicking "Done".
Displays the number of correctly typed words and total errors.
Running the Project:

Save the code as an HTML file (e.g., typing_test.html).
Open the HTML file in a web browser.
Click the "Start" button to begin the test.
Type the displayed sentence in the text area and click "Done" to see your results.
Code Structure:

index.html: Contains the HTML structure of the web page.
style.css: Defines the styling of the elements.
script.js: Contains the JavaScript logic for generating random sentences, calculating typing speed, and displaying results.
Technical Notes:

The script utilizes several functions:
playGames(): Generates a random sentence and starts the timer.
wordscounter(data): Counts the number of words in a given string.
compareWords(str1, str2): Compares the typed sentence with the original sentence and calculates accuracy.
endPlay(): Calculates typing speed, displays results, and resets the test.
The script uses event listeners to detect clicks on the "Start" button and handle functionality accordingly.
Future Enhancements:

Implement additional difficulty levels with varying sentence lengths or complexities.
Track user progress and display typing speed history.
Include a timer during the test to create a sense of urgency.
