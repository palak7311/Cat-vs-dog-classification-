# 🐱 Cat vs Dog Classification 🐶
### Deep Learning | CNN | Image Classification

<p align="center">
  <b>Teaching a machine to distinguish between Cats and Dogs using Deep Learning!</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img src="https://img.shields.io/badge/TensorFlow-Keras-orange?logo=tensorflow" />
  <img src="https://img.shields.io/badge/Deep%20Learning-CNN-purple" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

---

## ✨ About The Project

Can a machine tell the difference between a cat and a dog just by looking at an image?

This project explores that idea using **Convolutional Neural Networks (CNNs)**.

I developed a Deep Learning model that learns visual patterns and features from images to classify them into two categories: **Cat 🐱 or Dog 🐶**.

The project covers the complete workflow, from dataset preparation and image preprocessing to model training and real-image prediction.

## 🎯 Project Objectives

- Understand the practical implementation of CNN.
- Perform image preprocessing and normalization.
- Build a multi-layer CNN architecture.
- Train and validate a Deep Learning model.
- Predict categories from unseen input images.

## 📂 Dataset

The model uses the **Dogs vs Cats Dataset** from Kaggle.

🔗 [Explore Dataset on Kaggle](https://www.kaggle.com/datasets/salader/dogsvscats)

| Dataset Details | Information |
|---|---|
| Total Images | 25,000 |
| Training Images | 20,000 |
| Testing Images | 5,000 |
| Image Size | 256 × 256 |
| Number of Classes | 2 |
| Classes | Cat, Dog |

## ⚙️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| TensorFlow & Keras | Deep Learning Framework |
| CNN | Image Classification |
| NumPy | Numerical Operations |
| Matplotlib | Image Visualization |
| Google Colab | Development Environment |

## 🧠 CNN Architecture

The model is built using a Sequential CNN architecture.

**Architecture Overview:**

```text
Input Image (256 × 256 × 3)
          |
     Conv2D (32)
          |
 Batch Normalization
          |
      MaxPooling
          |
     Conv2D (64)
          |
 Batch Normalization
          |
      MaxPooling
          |
    Conv2D (128)
          |
 Batch Normalization
          |
      MaxPooling
          |
       Flatten
          |
    Dense (128)
          |
      Dropout
          |
     Dense (64)
          |
      Dropout
          |
    Dense (1)
          |
   Sigmoid Activation
          |
   Cat 🐱 / Dog 🐶
```

### 🔧 Model Configuration

- **Optimizer:** Adam
- **Loss Function:** Binary Crossentropy
- **Evaluation Metric:** Accuracy
- **Batch Size:** 32
- **Maximum Epochs:** 20
- **Early Stopping:** Used to prevent unnecessary training.

## 📊 Model Performance

The model achieved the following training results:

| Metric | Result |
|---|---|
| Highest Recorded Validation Accuracy | 79.96% |
| Training Epochs Completed | 6 |
| Early Stopping | Triggered |

*Note: 79.96% is the highest validation accuracy observed during training, not an independently evaluated final test accuracy.*

## 🖼️ Project Results

### 1. Model Training

Add your training output screenshot here.

### 2. Image Prediction

The model was tested with a cat image and successfully predicted:

**Prediction: Cat 🐱**

Add your prediction screenshot here.

## 🚀 How To Run This Project

**Step 1:** Clone the repository.

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

**Step 2:** Open the notebook in Google Colab.

**Step 3:** Download the dataset from Kaggle.

**Step 4:** Configure the dataset and image paths.

**Step 5:** Run all notebook cells sequentially.

**Step 6:** Test the model using a cat or dog image.

## 📁 Repository Structure

```text
Cat-VS-Dog-Classification/
│
├── Cat-VS-Dog Classification.ipynb
├── README.md
│
└── screenshots/
    ├── training-output.png
    └── prediction-output.png
```

## 💡 Key Learnings

Through this project, I gained practical experience in:

- Building CNN models from scratch.
- Understanding convolution and pooling operations.
- Image preprocessing and normalization.
- Training and validating neural networks.
- Using TensorFlow and Keras.
- Making predictions on custom images.

## 🔮 Future Improvements

- Improve classification accuracy.
- Experiment with data augmentation.
- Implement Transfer Learning using MobileNetV2.
- Build an interactive image classification web application.

---


B.Tech | Computer Science & Engineering (AI)

Interested in Artificial Intelligence, Machine Learning and Deep Learning.

<p align="center">
  ⭐ If you find this project interesting, consider giving this repository a star!
</p>
