# 🎭 Face Detection and Recognize

A beginner-friendly Python project that detects and recognizes human faces in real-time using a webcam.

---

## 📸 What It Does

When you run this project, it opens your webcam, detects faces and tells you **who the person is** based on trained data.

- ✅ Trains a face recognition model from your dataset
- ✅ Opens webcam and scans every frame
- ✅ Detects faces using Haar Cascade algorithm
- ✅ Draws a **green box** around every detected face
- ✅ Displays the **person's name** if recognized
- ✅ Displays **"Unknown"** if face is not recognized
- ✅ Saves a photo as `input.jpg` if unknown person appears 100+ times
- ✅ Press **`ESC`** to quit anytime

---

## 🛠️ Libraries Used

| Library | Why |
|--------|-----|
| `opencv-python` | Webcam access, image processing, face detection |
| `numpy` | Handling image arrays for model training |
| `os` | Reading dataset folders and files |
| `haarcascade_frontalface_default.xml` | Pre-trained face detection model |
| `FisherFaceRecognizer` | OpenCV face recognition model |

---

## ⚙️ Installation

Make sure Python is installed, then run:

```bash
pip install opencv-python numpy opencv-contrib-python
```

---

## 📂 Project Structure