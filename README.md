# 🚗 Vehicle Detection and Counting Using CNN

This project uses computer vision techniques to detect and count vehicles in a video using OpenCV and background subtraction. The main goal is to track moving vehicles in a video feed and count them as they pass a designated line.

---

## 📽️ Demo
The script processes a file named `video.mp4`. Make sure the video file is present in the same directory as the Python script.

---

## 🧠 Features
- Vehicle detection using background subtraction (MOG)
- Vehicle tracking and counting using contour detection
- Live bounding boxes and center point drawing
- Line-crossing detection logic
- Real-time vehicle count display

---

## 📦 Files
- `vehicle.py` – Main Python script for detection and counting
- `video.mp4` – Sample video file (add your own if not present)

---

## 🛠️ Requirements

Install the required Python packages using:

```bash
pip install opencv-python opencv-contrib-python numpy
