# Zero-input-AUTO
Zero input AUTO is a software designed to be able to record mouse movements, button pressing and more! . Its made for automatisation and can play off files. Very easy to use.  Since its free to use and doesn't have any type of lisence you can use it, copy it, remix it or do whatever you want to!

It automaticly resizes to your screen size for maximum presision.

Installation prosess:
Go to realeases and download the latest version.
Run the program.
If asked by windows please click "more info" and then "run anyways". (this is necessary because i am not a verified publisher)
The program should run like normal and adjust to your screen size.
Use "ESC" to stop recording or to stop playback.

Remember where you put the files and dont use any windows program folders like "system32".

How to use ZIAv3:

ZIAv3 User Guide
ZIAv3 is a desktop app for recording and replaying mouse and keyboard actions with visual feedback, speed control, macro support, and preview capabilities. Use it to automate repetitive tasks, create tutorials, or test UI workflows. Follow the steps below to get started.

Launching ZIAv3
Install or run the application by double-clicking the ZIAv3.exe file (if packaged) or executing the Python script. The main window appears with controls for recording, playback, point mapping, and preview. A transparent overlay window sits on top to show cursor trails and click animations.

Recording Input
To capture your actions:

Click Start Recording.
Perform mouse movements, clicks, scrolls, and keystrokes as needed.
Watch the status label for “Recording… Press ESC to stop.”
Press the Esc key to end recording.
Choose a filename in the save dialog and click Save.
Your input is saved as a JSON file containing screen size, mouse events, and keyboard events.
Playing Back Recordings
To replay a saved session:

Click Play Recording.
Select the JSON file you recorded earlier.
Use the Enable Mouse and Enable Keyboard checkboxes to include or exclude input types.
Adjust the Playback Speed slider (0.2× to 2.0×) to slow down or speed up the replay.
Press Esc at any time to stop playback.
During playback you’ll see gray trails for movement and colored circles (red for left clicks, blue for right clicks).
Point Mapping Mode
Map specific screen coordinates without full recording:

Click Point Mapping Mode.
Move the cursor to a point and press F to record a move event.
Press D to record a left-click at the current position.
Continue adding points or clicks as needed.
Press Esc to finish mapping.
Save the mapping to a JSON file when prompted.
This mode is ideal for creating scripts that target fixed UI elements.
Preview Mode
Visualize recorded mouse actions before replaying:

Click Preview Recording.
Select your JSON file.
A preview window opens (800×600) showing small black dots for moves and colored outlines for clicks.
Examine the path and adjust your recording if needed.
Preview mode helps verify accuracy without executing any real clicks or keystrokes.
Controls and Settings

Playback Speed slider adjusts the delay multiplier for all events.
Enable Mouse / Enable Keyboard toggles let you isolate input types.
Status Label at the top displays current mode, errors, and completion messages.
Click animations and trails always run on the transparent overlay to avoid interfering with your workflow.
Tips for Best Results

Record at your normal screen resolution for accurate replay scaling.
Use point mapping for fixed-position interfaces to reduce noise.
Combine macros by editing the JSON file to add "repeat" or "wait_for_key" entries.
Package the app with PyInstaller to share the .exe file with others.
Test small segments first to fine-tune speed and visual settings.
You’re now ready to harness the full power of ZIAv3. Automate, test, and showcase your workflows with precision and flair!
