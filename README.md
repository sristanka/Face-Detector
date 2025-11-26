# Face-Detector

## About the Project

This is my first real-time face detection project! 🟢🔵🟡  

I built a system using **Python** and **OpenCV** that can detect:  

- **Faces** 🟢  
- **Eyes** 🔵  
- **Smiles / Mouth** 🟡  

It works **live with your webcam**, showing colored rectangles around each feature.  

This project is a fun way to see how computers can “see” faces, and it’s a great beginner project for learning **computer vision**.

---

## Features

- Detects **faces, eyes, and smiles** in real-time.  
- Eyes are detected only in the **upper half of the face** to reduce false positives.  
- Smile/mouth detection works reliably inside the face area.  
- Supports **multiple faces** at once.  
- Lightweight and runs smoothly on regular laptops.

---

## Demo

*(Add a short GIF or screenshot showing your webcam detecting face, eyes, and smile here)*  

---

## How to Use

**Clone the repo**  
```bash
git clone https://github.com/sristanka-adhikary/Face-Detector.git
````
**Install dependencies**
```bash
pip install opencv-python
```
**Run the project**
```bash
python facedetect.py
```
Then, your webcam will turn on and detect your face, eyes, and smile in real-time.

How It Works

Captures live video from your webcam.

Converts each frame to grayscale for faster detection.

Detects faces with a Haar cascade.

Detects eyes in the upper half of the face.

Detects smile/mouth inside the face.

Draws colored rectangles around each feature:

Face → Green

Eyes → Blue

Smile → Yellow

Technologies Used

Python

OpenCV (Computer Vision)

Haar Cascade Classifiers

Future Improvements

Add fun filters like sunglasses or hats.

Detect facial landmarks for more precise feature tracking.

Auto screenshot when someone smiles.

Turn it into a GUI application for easier use.

Author

SRISTANKA ADHIKARY – 2nd-year Biotechnology BTech student exploring coding, AI, and computer vision.

License

This project is licensed under the MIT License – see the LICENSE
 file for details.



