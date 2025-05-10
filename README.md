Morse Code Translator
A simple GUI-based application built using Java that translates text into Morse code and allows audio playback of the Morse code as beeps.

Features:
Text Translation: Converts text input into Morse code.

Morse Code Playback: Plays the Morse code as beeps (dot and dash) through the computer's speakers.

GUI Interface: User-friendly interface built with Swing for ease of use.

Key Listener: Allows real-time translation as the user types in the input area.

Technology Stack:
Java: Core programming language.

Swing: GUI framework for the graphical user interface.

Java Sound API: To generate audio beeps for Morse code playback.

How It Works:
Text Input: The user can input text (including letters, numbers, and special characters) in the "Text" area.

Translation: The app translates the text into Morse code and displays it in the "Morse Code" area.

Sound Playback: The user can click the "Play Sound" button to hear the translated Morse code as beeps, where:

A dot (.) is represented as a short beep.

A dash (-) is represented as a longer beep.

A space between words is represented by silence.

Usage Instructions:
Running the Application:

Download or clone the repository.

Open the project in your Java IDE (e.g., IntelliJ IDEA or Eclipse).

Run the App.java file to launch the application.

Using the GUI:

Type or paste the text you want to translate into the "Text" input area.

The translated Morse code will automatically appear in the "Morse Code" area.
Press the "Play Sound" button to listen to the Morse code being played.





Project Files:
App.java: The main entry point that initializes the GUI and launches the application.

MorseCodeController.java: The controller class responsible for the translation logic and playing the Morse code sounds.

MorseCodeTranslatorGUI.java: The GUI class that sets up the graphical interface and handles user interactions.

Code Structure:
MorseCodeController:

HashMap to store the mappings of letters and numbers to their corresponding Morse code.

Method translateToMorse converts the text to Morse code.

Method playSound plays the Morse code using the system's audio system.

MorseCodeTranslatorGUI:

Swing components for displaying the input text and translated Morse code.

Key listener for capturing the text input in real-time.

Requirements:
Java 8 or above to run the application.

License:
This project is licensed under the MIT License - see the LICENSE file for details.

