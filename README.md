# Quiz App

## Overview
The **Quiz App** is a Flutter-based application designed to test users' knowledge through a series of quiz questions. The app offers an intuitive interface, engaging visuals, and tracks the highest scores achieved by players.

## Features
- **Start Screen**: Initiates the quiz experience with a welcoming message and a "Start Quiz" button.
- **Question Screen**: Displays one question at a time, allowing users to select their answers.
- **Results Screen**: Shows the results after completing the quiz, including the number of correct answers and the best score.
- **Answer Summary**: Provides a summary of the questions answered, highlighting correct and incorrect responses.
- **Restart Functionality**: Allows users to restart the quiz and attempt to beat their previous best score.

## File Structure

/quizz_app
- main.dart              # Entry point of the application
- start_screen.dart      # Widget for the start screen
- questions_screen.dart   # Widget for displaying questions
- results_screen.dart     # Widget for displaying results
- answer_button.dart      # Widget for the answer button
questions_summary/      # Folder containing summary-related widgets
- question_identifier.dart  # Widget for question identifiers
- summary_item.dart         # Widget for individual summary items
- questions_summary.dart     # Widget for the summary of questions
data/
- questions.dart         # Contains the quiz questions and answers
- pubspec.yaml              # Package configuration

## Getting Started
Prerequisites
Flutter SDK installed on your machine.
An IDE such as Android Studio, VS Code, or IntelliJ IDEA.

## Installation
**Clone the repository:**
git clone <repository-url>
cd quizz_app

## Install the dependencies:
flutter pub get

## Run the application:
flutter run

## Usage
- Launch the app to see the start screen.
- Tap on the "Start Quiz" button to begin.
- Select answers for each question presented.
- Once all questions are answered, review the results, including the best score.
- Use the "Restart Quiz" button to take the quiz again.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the NTNU License. See the [LICENSE](./LICENSE) file for more details.

