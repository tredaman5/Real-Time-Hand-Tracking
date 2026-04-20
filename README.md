# 🖐️ Real-Time Hand Tracking

A real-time hand tracking system built using computer vision. This project uses a webcam to detect and track hand landmarks, enabling gesture-based interaction.

---

## 🚀 Features

- Real-time hand detection using webcam
- Tracks hand landmarks (fingers, joints)
- Supports multiple hands
- Lightweight and fast
- Built with industry-standard computer vision tools

---

## 🛠️ Tech Stack

- Python 3.10
- OpenCV
- MediaPipe

---

## ⚠️ Requirements

This project uses the legacy MediaPipe Solutions API.

Make sure you are using:

- Python **3.10**
- `mediapipe==0.10.21`

---

## 📦 Installation

### 1. Clone the repository

git clone https://github.com/tredaman5/Real-Time-Hand-Tracking.git  
cd Real-Time-Hand-Tracking

### 2. Create a virtual environment

py -3.10 -m venv venv  
venv\Scripts\activate

### 3. Install dependencies

pip install -r requirements.txt

---

## ▶️ Running the Project

python main.py

- A webcam window will open  
- Your hand will be detected and tracked in real-time  
- Press **q** to quit  

---

## 🧠 How It Works

1. Captures video from your webcam using OpenCV  
2. Converts frames to RGB format  
3. Uses MediaPipe Hands model to detect landmarks  
4. Draws hand connections and key points on the frame  
5. Displays the processed video in real-time  

---

## 📸 Demo

(Add a GIF or screenshot here — highly recommended)

![Demo](demo.gif)

---

## 🔧 Project Structure

Real-Time-Hand-Tracking/  
│  
├── main.py  
├── requirements.txt  
├── README.md  
├── LICENSE  
└── .github/  
    └── workflows/  
        └── ci.yml  

---

## 🔄 Future Improvements

- Gesture recognition (e.g., thumbs up, pinch)  
- Finger counting system  
- Volume or brightness control via gestures  
- Performance optimization (FPS tracking)  
- UI improvements  

---

## 🤖 CI/CD

This project uses GitHub Actions to:

- Validate Python environment (3.10)  
- Install dependencies  
- Check imports  
- Validate code syntax  

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

- Google MediaPipe  
- OpenCV  