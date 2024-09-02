# Hand Gesture Paint App

This is a Python-based application that allows users to paint on a virtual canvas using hand gestures. The app utilizes computer vision and machine learning techniques to detect hand gestures in real-time, enabling users to draw, erase, and change colors without touching a mouse or keyboard.

## Features

- **Real-time Hand Gesture Detection**: Uses OpenCV and MediaPipe to detect hand gestures.
- **Virtual Canvas**: Draw on a digital canvas with simple hand movements.
- **Gesture Controls**: Switch between drawing, erasing, and changing colors with intuitive gestures.
- **Dynamic Brush Size**: Adjust brush size using specific hand movements.
## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.6+
- OpenCV (`opencv-python`)
- MediaPipe (`mediapipe`)
- NumPy
- PyAutoGUI (optional, for advanced gesture controls)

You can install these dependencies using pip:

```bash
pip install opencv-python mediapipe numpy pyautogui
