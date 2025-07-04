🔆 Real-Time Brightness Controller using OpenCV
This project demonstrates how to adjust the brightness of an image in real-time using OpenCV's Trackbar GUI feature. The user can interactively increase or decrease brightness through a slider.

📷 Features
Loads an image (car.jpg)

Creates a GUI window with a brightness slider (trackbar)

Real-time brightness control using cv.add() and cv.subtract()

Brightness value ranges from 0 to 255 (midpoint = neutral)

🧠 How It Works
The trackbar value is centered at 127:

Moving the slider right ( >127 ) increases brightness

Moving the slider left ( <127 ) decreases brightness

Image brightness is adjusted using:

cv.add(img, value) to brighten

cv.subtract(img, value) to darken

📁 File Structure
Copy
Edit
├── images/
│   └── car.jpg
├── brightness_controller.py
└── README.md
🛠️ Requirements
Python 3.x

OpenCV

NumPy

Install dependencies with:

bash
Copy
Edit
pip install opencv-python numpy
▶️ How to Run
bash
Copy
Edit
python brightness_controller.py
Move the slider to adjust brightness

Press ESC (Escape key) to exit

📸 Preview


💡 Credits
Made with OpenCV’s createTrackbar() and real-time image processing.

Developed by Parth Sawant
