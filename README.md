# Eye Controlled Scroll

A Python project that allows you to control screen scrolling using your eye movements through a webcam. It detects your gaze direction and scrolls the screen up or down accordingly.

---

## Features

- Real-time eye tracking using MediaPipe
- Scroll up when looking up
- Scroll down when looking down
- No scrolling when looking straight
- Adjustable sensitivity and scroll speed
- Optional preview window

---

## How It Works

The program uses MediaPipe FaceLandmarker to detect facial landmarks, including the iris. It calculates the position of the iris relative to the eye and determines whether the user is looking up, down, or center.

Based on this:
- Looking up triggers upward scrolling
- Looking down triggers downward scrolling

---

## Requirements

Install the required libraries:

```bash
pip install opencv-python mediapipe pyautogui
