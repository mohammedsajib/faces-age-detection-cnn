# 🧠 Faces Age Detection using CNN

A PyTorch-based **Convolutional Neural Network (CNN)** project for classifying facial images into three age groups: **Young, Middle, and Old**.

## 📌 Overview

This project covers image preprocessing, augmentation, CNN training, validation, and model evaluation using the **Faces Age Detection** dataset.

## 🛠️ Tech Stack

* Python
* PyTorch & Torchvision
* NumPy & Pandas
* Scikit-learn
* Matplotlib & Seaborn
* Google Colab / NVIDIA Tesla T4

## 🧠 Model

Custom CNN with multiple convolutional and fully connected layers.

**Input:** `224 × 224 RGB`
**Classes:** `YOUNG | MIDDLE | OLD`
**Optimizer:** Adam
**Loss:** CrossEntropyLoss
**Epochs:** 10
**Batch Size:** 32

## 📊 Results

| Metric                   |      Score |
| ------------------------ | ---------: |
| Training Accuracy        | **83.43%** |
| Best Validation Accuracy | **79.86%** |
| Validation Loss          | **0.4974** |
| Weighted F1-Score        |   **0.79** |

### Classification Performance

| Class  | Precision | Recall |   F1 |
| ------ | --------: | -----: | ---: |
| YOUNG  |      0.87 |   0.69 | 0.77 |
| MIDDLE |      0.76 |   0.94 | 0.84 |
| OLD    |      0.84 |   0.45 | 0.59 |

## 📈 Results Visualization

Add training/validation curves and confusion matrix in the `results/` folder.

## 📁 Project Structure

```text
faces-age-detection-cnn/
├── README.md
├── age_classification.ipynb
├── requirements.txt
├── .gitignore
└── results/
    ├── training_validation_loss.png
    ├── training_validation_accuracy.png
    └── confusion_matrix.png
```

## 🚀 Future Improvements

* Transfer learning with ResNet/EfficientNet
* Better data augmentation
* Class-weighted loss
* Learning-rate scheduling
* Hyperparameter tuning

## 👨‍💻 Author

**Mohammed Sajib**
Computer Science Student | AI/ML Enthusiast

⭐ If you find this project useful, consider starring the repository.
