# ✋ Real-Time Sign Language Interpretation Using Image Recognition

This project implements a **real-time sign language detection system** using a hybrid **CNN + LSTM deep learning model**. It allows users to perform sign gestures in front of a camera, which are then interpreted and translated instantly — helping bridge communication gaps for individuals with hearing impairments.

---

## 🧠 Overview

- 🧾 **Goal**: Recognize and interpret sign language gestures in real time
- 🧩 **Model**: Combines **Convolutional Neural Networks (CNNs)** for spatial feature extraction and **Long Short-Term Memory (LSTM)** networks for temporal sequence learning
- 📹 **Input**: Live video stream
- 📤 **Output**: Recognized sign gesture displayed as text
- 🧑‍💻 **Built With**: Python, TensorFlow, OpenCV, NumPy

---

## 🎯 Features

- 📡 Real-time gesture recognition from webcam input
- 🔍 High-accuracy prediction (95% on test data)
- ➕ Option to add and train new gestures
- 🌐 Assistive technology for the deaf and hard-of-hearing community
- 🧰 Easily customizable and extensible

---

## 🧪 Methodology

### 📁 Data Collection & Preprocessing
- Dataset of labeled sign language gesture videos
- Key frames extracted and normalized (e.g., 224x224 pixels)
- Sequential frame stacking to represent gestures as time-series data

### 🧠 Model Architecture
- **CNN Layers**: Extract features from individual frames
- **LSTM Layers**: Learn temporal relationships between frames
- **Dense Layers**: Classify into predefined gesture classes
- **Softmax Output**: Predict gesture with confidence score

### ⚙️ Training Details
- Batch size: 32  
- Epochs: 50  
- Optimizer: Adam  
- Loss: Categorical Crossentropy  
- Techniques: Data augmentation, dropout, validation split

---

## 📈 Results

- ✅ **Accuracy**: 95% on test set
- 📊 Evaluated using accuracy, precision, recall, and F1-score
- 🖥️ Real-time performance tested on webcam stream
- ⏱️ Minimal delay in prediction, suitable for live applications

---

## 🧩 Challenges & Future Work

- 🔦 Improve robustness to lighting/background variations
- 🔄 Enable custom gesture training via user input
- 🌍 Expand support for different sign languages
- 🚀 Explore transformer-based models for continuous gesture streams

