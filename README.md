# 🌾 Paddy Disease Detection using Deep Learning

An AI-powered web application that detects diseases in paddy (rice) leaves using deep learning. This project uses a **MobileNetV2-based convolutional neural network** to classify leaf images into different disease categories and provides treatment recommendations.

---

## 🚀 Features

* 🌿 Upload or capture paddy leaf images
* 🧠 Deep learning-based disease prediction
* 📊 Displays prediction with confidence score
* 💊 Provides treatment and prevention suggestions
* ⚠️ Detects and rejects non-paddy images

---

## 🦠 Diseases Detected

* Bacterial Blight
* Blast
* Brown Spot
* Non-Paddy (invalid input detection)

---

## 🏗️ Tech Stack

* Python
* TensorFlow / Keras
* MobileNetV2 (Transfer Learning)
* Streamlit (Web App UI)
* NumPy, OpenCV, Pillow

---

## 📂 Project Structure

```
paddy-disease-detection/
│
├── app.py              # Streamlit frontend
├── model.py            # Model loading & prediction
├── ragi_model.keras    # Trained deep learning model
├── dataset/            # Training dataset
├── train_model.ipynb   # Model training notebook
├── requirements.txt
└── README.md
```

---

## 🧠 Model Details

* Pre-trained MobileNetV2 used for feature extraction
* Input size: 224 × 224 RGB images
* Data augmentation applied for better generalization
* Achieves reliable classification on common paddy diseases

---

## ▶️ How to Run

```bash
# Clone repository
git clone https://github.com/your-username/paddy-disease-detection.git

# Navigate to project
cd paddy-disease-detection

# Create virtual environment
python -m venv venv

# Activate environment
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run application
streamlit run app.py
```

---

## 📌 Use Cases

* Farmers for early disease detection
* Agricultural research and education
* Smart farming solutions
* AI-based crop monitoring systems

---
