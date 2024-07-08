# Sudokusensei-solver-react (OCR feature - image processing)

Sudokusensei-solver-react is a web application designed to solve Sudoku puzzles using OCR (Optical Character Recognition) for image processing. The application allows users to input Sudoku puzzles, which are then solved and displayed on the screen.

## Features

- **Sudoku Solver**: Automatically solves Sudoku puzzles provided by the user.
- **OCR Image Processing**: Under maintenance, will soon support solving Sudoku puzzles from images.
- **User Authentication**: Allows users to sign up or log in via Firebase authentication.
- **Home Page**: Users have the option to proceed without logging in by clicking on the Home button.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Flask
- **Database**: Firebase (for user authentication)
- **Hosting**: PythonAnywhere

## Usage

To run the application locally:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Sudokusensei-solver-react
   ```

2. Install dependencies:
   ```bash
   # Assuming npm is used for React.js frontend
   npm install
   ```

3. Start the Flask server:
   ```bash
   python app.py
   ```

4. Launch the React frontend:
   ```bash
   npm start
   ```

5. Access the application in your web browser at `http://localhost:3000`.

## Installation

To install Sudokusensei-solver-react and its dependencies, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Sudokusensei-solver-react
   ```

2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Install React dependencies:
   ```bash
   npm install
   ```

4. Configure Firebase:
   - Create a Firebase project and configure Firebase authentication in `firebase.js`.

5. Run the application:
   - Start the Flask server: `python app.py`
   - Launch the React frontend: `npm start`

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your suggested changes.

## Acknowledgments

- **Firebase**: Used for user authentication.
- **Flask**: Backend server framework.
- **React**: Frontend framework.
- **PythonAnywhere**: Hosting platform.
