# Hand-Gesture-Based-Mouse-Control-System
https://tinyurl.com/N34-slide
https://tinyurl.com/N34-report
https://tinyurl.com/N34-web
https://tinyurl.com/n34-poster
---

This project allows the user to control the mouse cursor and perform mouse clicks using hand gestures. The system uses the **MediaPipe** library for hand landmark detection and **PyAutoGUI** for simulating mouse actions. By tracking the user's hand position and finger movements via a webcam, the program enables interaction with the computer in an intuitive and hands-free way.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation Instructions](#installation-instructions)
- [How to Use](#how-to-use)
- [Exiting the Program](#exiting-the-program)
- [License](#license)

## Features

1. **Move Mouse Cursor**:  
   By holding the hand tight with the **index** and **middle finger** pointing upwards, the user can control the mouse cursor's movement on the screen.

2. **Left-Click**:  
   When the **index finger** is folded (making a fist), it triggers a **left-click** action on the mouse.

3. **Right-Click**:  
   When the **middle finger** is folded (making a fist), it triggers a **right-click** action on the mouse.

4. **Exit Program**:  
   By folding both the **index** and **middle fingers** simultaneously, the user can close the program.

## Requirements

Before running the program, make sure you have the following libraries installed:

- **Python 3.x**  
- **MediaPipe**: Used for hand gesture detection and landmark tracking.
- **PyAutoGUI**: Used for controlling mouse actions such as clicks and cursor movements.
- **OpenCV**: Used for capturing the webcam feed.

You can install the required libraries using pip:

```bash
pip install mediapipe pyautogui opencv-python
```

## Installation Instructions

1. Clone or download the project files to your local machine.

2. Install the required dependencies using the command above.

3. Connect a **webcam** to your computer for real-time hand gesture recognition.

4. Run the program with the following command:

```bash
python gesture_mouse_control.py
```

This will open a window displaying the webcam feed and tracking hand gestures.

## How to Use

### Mouse Cursor Movement:
- **Gesture**: Hold your hand tight with the **index finger** and **middle finger** pointing straight up.
- **Action**: The program will detect the position of your fingers, and as you move your hand, the cursor will move on the screen accordingly.

### Left-Click:
- **Gesture**: Fold your **index finger** (while keeping the other fingers extended).
- **Action**: This will trigger a **left-click** on the mouse, as if you had clicked the mouse button manually.

### Right-Click:
- **Gesture**: Fold your **middle finger** (while keeping the other fingers extended).
- **Action**: This will trigger a **right-click** on the mouse.

### Exit Program:
- **Gesture**: Fold both the **index finger** and **middle finger** simultaneously.
- **Action**: This will cause the program to exit immediately.

## Exiting the Program

To exit the program, simply fold both the **index** and **middle fingers** simultaneously. This will close the program window and stop the webcam feed.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---
