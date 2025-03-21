# 🚗 Lane Detection System

## 📌 Overview

This project implements a **Lane Detection System** using **OpenCV** and **NumPy**. The system processes a video stream to detect lane markings on the road using edge detection and the Hough Transform.

## ✨ Features

✅ **Real-time lane detection** from video input\
✅ **Edge detection** using Canny Edge Detector\
✅ **Region of Interest (ROI) filtering** to focus on relevant areas\
✅ **Hough Line Transform** to detect lane lines\
✅ **Overlay lane lines** on the original video

## 🛠 Installation

### **Prerequisites**

Ensure you have **Python 3.x** installed. You can install the required dependencies using:

```bash
pip install opencv-python numpy matplotlib
```

## 🚀 Usage

### **Run the Lane Detection System**

```bash
main.py
```

### **Project Structure**

```
|-- main.py                 # Main script for lane detection
|-- test2.mp4               # Sample test video (Replace with your own video)
|-- README.md               # Project documentation
```

## 🧑‍💻 Code Explanation

### **1. Edge Detection and Region Selection**

- Converts the video frame to **grayscale**
- Applies **Canny Edge Detection** to highlight lane edges
- Uses a **Region of Interest (ROI)** to filter unnecessary details

### **2. Lane Detection Using Hough Transform**

- Applies **Hough Line Transform** to detect straight lines
- Draws detected lane lines onto the original video frame

### **3. Displaying the Output**

- Processes each frame of the video
- Displays the video output with detected lanes

## 📷 Example Output

The program reads frames from `test2.mp4`, detects lanes, and displays the output with overlayed lane lines.
![image alt](https://github.com/reyansh2002/lane-detection-system-computer-vision-/blob/main/output.png)

## 🔥 Improvements & Future Work

🔹 Implement **deep learning** for more accurate lane detection under different lighting conditions\
🔹 Improve **lane tracking** using Kalman Filters or Deep Learning models\
🔹 Add **curved lane detection** using polynomial fitting

## 👨‍💻 Author

Reyansh Singh
[B.tech-CSE-AI & ML]

---

Give this project a ⭐ if you found it useful!
