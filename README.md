# Music_Player_with_Java

This is a small Java project I built to understand how Java interacts with external files, like audio files.
My idea was to create a simple music player that can play, stop, and reset a .wav audio file.

#### The project mainly helped me understand:

- how to work with packages and folders,

- how file paths work,

- how Java handles audio streams,

- and how user input can control a running program.

When the program starts, it loads the audio file using Java’s sound library. After it loads, the program keeps asking the user what they want to do — whether to play the audio, stop it, reset it to the beginning, or quit the program.

The good thing is, it works using a loop, so the program keeps running until the user presses 'Q'. The audio itself is stored inside the project folder, and Java reads it as a file.

This project really helped me understand how Java handles external resources and user interactions.






## 🚀 How to Run the Project
#### Step 1: Clone the Repository

git clone <your-github-link>

#### Step 2: Open in Eclipse

Go to File → Import → Existing Java Project

Select the folder

Finish

#### Step 3: Make Sure the Audio File Exists

Check this path inside the project:

- src/my_first_project/audio/good_for_the_ghost_Alge.wav

#### Step 4: Run the Program

Right-click → Run As → Java Application

