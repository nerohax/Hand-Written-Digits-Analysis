# ✍️ Handwritten Digits Recognition using CNN  

## 📌 Project Overview  
This project focuses on **classifying handwritten digits (0-9) from the MNIST dataset** using **Convolutional Neural Networks (CNNs)**. The goal is to develop a deep learning model that can accurately recognize and classify handwritten numbers, making it useful for applications like digit recognition in postal services, banking, and automation.  

## 🔍 Problem Statement  
Handwritten digit recognition is a fundamental problem in **computer vision** and **optical character recognition (OCR)**. This project builds a **deep learning model** using CNNs to automatically identify digits from images, ensuring high accuracy and efficiency.  

## 🚀 Approach  

### 1️⃣ Data Preprocessing  
- Loaded the **MNIST dataset** (60,000 training + 10,000 test images).  
- Normalized pixel values to scale between `0-1`.  
- Applied **data augmentation** (rotation, zoom, shifting) to improve generalization.  

### 2️⃣ Model Development  
- Implemented a **CNN architecture** with:  
  ✅ **Convolutional Layers** for feature extraction  
  ✅ **Max Pooling** for dimensionality reduction  
  ✅ **Fully Connected Layers** for classification  
- Used **ReLU activation** for non-linearity and **Softmax** for multi-class classification.  

### 3️⃣ Model Training & Optimization  
- **Loss Function:** Categorical Cross-Entropy  
- **Optimizer:** Adam  
- **Regularization:** Dropout to prevent overfitting  
- **Early Stopping:** Stops training when validation loss stops improving  

### 4️⃣ Evaluation Metrics  
- **Accuracy:** `99%`  
- **Precision & Recall:** High across all digit classes  
- **Confusion Matrix & Classification Report** used for detailed analysis  

## 📊 Results  
✅ Achieved **99% accuracy** on the MNIST test dataset.  
✅ Successfully recognized handwritten digits with **high precision & recall**.  
✅ Developed a **deployable CNN-based digit recognition model**.  
