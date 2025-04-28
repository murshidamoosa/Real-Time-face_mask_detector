# Real-Time-face_mask_detector

# Description

A deep learning-based real-time face mask detection system that detects whether people are wearing face masks or not using a webcam feed. 
Built using TensorFlow/Keras, OpenCV, and Flask.

# About

This project helps automate the process of monitoring face mask usage in public areas. 
It detects faces in live video streams and classifies them as "Mask" or "No Mask" in real time.

# Technologies

- Python 3
- TensorFlow / Keras
- OpenCV
- Flask (optional, if you deployed)

#  Setup Instructions

1. Clone the repository
   git clone https://github.com/your-username/your-repo-name.git

2. Install the required packages
   pip install -r requirements.txt

3. Make sure you have Haar Cascade file:
   haarcascade_frontalface_default.xml

4. Train the model (or use the saved model 'mymodel.h5').

5. Run the live detector script
   python facemask_detector.py

# How to Run

- Webcam will open.
- Face is detected and classified as:
    - MASK (green box)
    - NO MASK (red box)
- Press 'q' to quit the webcam window.

# Result

✅ Real-time mask detection  
✅ High accuracy  
✅ Smooth video streaming


# Future improvment

- Improve detection under different lighting and angles.
- Classify mask types (cloth, surgical, N95).
- Build a full web dashboard to monitor multiple cameras.
