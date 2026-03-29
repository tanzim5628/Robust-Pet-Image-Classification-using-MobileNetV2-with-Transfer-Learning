# 🐶🐱 Robust Pet Image Classification using MobileNetV2 (Transfer Learning)

## 📌 Overview

This project presents a **robust deep learning-based image classification system** that distinguishes between **cats and dogs** using **MobileNetV2 with transfer learning**. The model is optimized for efficiency and accuracy, making it suitable for real-world applications and deployment on resource-constrained devices.

---

## 🚀 Key Features

* 🔹 Transfer Learning using MobileNetV2 (pre-trained on ImageNet)
* 🔹 Efficient and lightweight architecture
* 🔹 Image preprocessing and resizing (160x160)
* 🔹 Real-time prediction on custom images
* 🔹 Model saving and reloading for inference
* 🔹 Visualization of predictions

---

## 🧠 Model Architecture

* Base Model: **MobileNetV2 (pre-trained)**
* Custom Layers:

  * Global Average Pooling
  * Dense Layer(s)
  * Sigmoid Activation for Binary Classification
* Loss Function: Binary Crossentropy
* Optimizer: Adam

---

## 📂 Dataset

* Dataset consists of labeled images of:

  * 🐶 Dogs
  * 🐱 Cats
* Images are preprocessed and resized before training.

---

## ⚙️ Workflow

1. Data loading from directory
2. Image preprocessing and normalization
3. Model building using transfer learning
4. Training and validation
5. Model saving
6. Prediction on new images

---

## 📊 Results

* Achieved strong classification performance on test images
* Successfully predicts whether an image is a **cat or dog**
* Demonstrates robustness on unseen images

---

## 🖼️ Sample Prediction

The model takes an input image and outputs:

* 🐶 Dog (if probability > 0.5)
* 🐱 Cat (otherwise)

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* PIL

---

## 📌 Future Improvements

* Add more classes (multi-class classification)
* Deploy as a web or mobile application
* Improve accuracy with data augmentation
* Use advanced architectures (EfficientNet, Vision Transformers)

---

## 📎 How to Run

1. Clone the repository
2. Install dependencies
3. Update dataset path
4. Run training script
5. Test with custom images

---

## 💡 Conclusion

This project demonstrates how **transfer learning with MobileNetV2** can be effectively used to build a fast and accurate image classification system with minimal computational cost.

---

⭐ If you like this project, feel free to star the repository!
