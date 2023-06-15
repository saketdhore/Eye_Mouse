# Eye Mouse

Eye Mouse is a Python project that utilizes computer vision and facial landmark detection to track the user's eye movement and perform actions on the screen. This project demonstrates how to use OpenCV, Mediapipe, and PyAutoGUI libraries to create an eye-tracking application.

## How It Works

The program uses the computer's webcam to capture video frames. It applies facial landmark detection to identify the user's eye position in real-time. By tracking the movement of specific landmarks, the program determines the direction of the user's movement of his/her eye.

When the user blinks or maintains a specific eye position for a specified duration, the program performs an action on the screen using the PyAutoGUI library. In the provided example, a click action is performed when the user blinks. Specifically, when the user blinks his left eye.

## Usage

1. Clone the repository or download the source code files.
2. Compile the main.py file. 
3. Run the program in either an IDE or your command line.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
