# Eye-Ball-cursor-movement-using-open-cv-in-python
👁️ Wink Wizard: Eye-Controlled Cursor with Screenshot & Scroll
A Human-Computer Interaction (HCI) project that uses your eyes to control the mouse, perform clicks, scroll, take screenshots, and even close browser tabs — all hands-free using MediaPipe, OpenCV, and PyAutoGUI.

🧠 Features
👁️ Cursor Control using iris movement

👆 Left Click by winking the left eye

👉 Right Click by winking the right eye

📸 Take Screenshot by blinking both eyes for 3 seconds

🔁 Scroll by moving eyes vertically

❌ Close Tabs by looking at the bottom-left corner

🔊 One-Time Beep Sound on successful detection
🛠️ Technologies Used
Python 3.x

OpenCV

MediaPipe

PyAutoGUI

pynput

plyer

winsound (Windows-specific)
🚀 How It Works
Uses MediaPipe FaceMesh to detect facial landmarks (iris, eye borders).

Calculates Eye Aspect Ratio (EAR) to detect winks and blinks.

Maps the iris position to the screen to move the mouse.

Detects a prolonged blink to trigger screenshots.

Uses eye position for scrolling and tab closing logic.
