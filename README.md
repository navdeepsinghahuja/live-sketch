
# 🖌️ Live Sketch App using OpenCV

This project turns your webcam feed into a real-time pencil sketch using Python and OpenCV.

---

## 📸 What It Does

- Captures your live webcam video. 
- Applies grayscale + Gaussian blur + edge detection. 
- Inverts the result to give a sketch effect. 
- Displays it in a live OpenCV window.
- Press `Enter` to close the app.

---

## 🧠 Tech Used

- Python 3.x
- OpenCV
- NumPy

---

## ⚙️ Installation

Install required dependencies:

```bash
pip install opencv-python numpy
```

---

## 🚀 How to Run

1. Clone this repo or download the `.py` file:

```bash
git clone https://github.com/your-username/live-sketch-opencv.git
cd live-sketch-opencv
```

2. Run the script:

```bash
python sketch.py
```

3. A window titled **"Our Live Sketcher"** will open showing the sketch version of your webcam feed.

4. Press **Enter (Return key)** to exit.

---

## 💡 Note

- Google Colab **does not support webcam access**.
- Please run this locally using:
  - Terminal
  - VS Code
  - PyCharm
  - or Jupyter Notebook (with local webcam access)

---


This function takes each video frame and returns the sketch-style image.

---

## 🙌 Made with ❤️ by [Navdeep Singh Ahuja]
