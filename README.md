# 📟 Analog Gauge Reading with YOLOv8-Pose

This project demonstrates how to use a YOLOv8 pose estimation model to detect keypoints on analog gauges and calculate pressure values based on the needle's angle. It uses a custom synthetic dataset in COCO keypoint format and is designed to run efficiently in Google Colab.

---
## 📊 Results
![detection](https://github.com/user-attachments/assets/5f87251e-c36f-4dc4-8481-c3d3bfda1f76)

---

## 🚀 Features

- 🔧 Trains a pose model using **YOLOv11-Pose**
- 🧠 Infers keypoints of an analog gauge needle
- 📐 Calculates pressure from needle angle using trigonometry
- 📊 Visualizes results with overlaid keypoints and needle
- 🖼️ Works on synthetic datasets with minimal resources

---

## 📦 Setup

Open [`training_prediction.ipynb`](training_prediction.ipynb) in [Google Colab](https://colab.research.google.com/)

