# Quick-MCQS
![Quick-MCQS Screenshot](https://github.com/mskDev0092/Quick-MCQS/raw/main/screenshot.png)
## Description
Quick-MCQS is a quiz application built with HTML, CSS, and JavaScript, designed for practicing multiple-choice questions. It supports drag-and-drop JSON file uploads for custom quizzes, making it versatile for users to create and test their own question sets.

## Features
- Interactive multiple-choice questions
- Drag-and-drop JSON file upload for custom quizzes
- Timer for timed quizzes
- Undo option to correct answers
- Responsive design for mobile and desktop

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mskDev0092/Quick-MCQS.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Quick-MCQS
   ```
3. Open `index.html` in a web browser.

## Usage
- Open the application in a browser.
- Drag and drop a JSON file with quiz data or select a built-in quiz topic.
- Start a timed quiz, answer questions, and use the undo option if needed.
- View results upon completion.

## JSON File Format
To create a custom quiz, use a JSON file with the following structure:
```json
[
  {
    "question": "Sample question?",
    "options": ["Option 1", "Option 2", "Option 3", "Option 4"],
    "correct": 0
  }
]
```

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License.
