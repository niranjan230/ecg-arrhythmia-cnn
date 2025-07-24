#  ECG Arrhythmia Classification using 1D-CNN

This project implements a deep learning model using a **1D Convolutional Neural Network (1D-CNN)** to classify ECG signals into different types of arrhythmias. It aims to support early detection of cardiac irregularities using time-series ECG data.

---

##  Model Overview

- **Model:** 1D CNN
- **Input:** 1D ECG signal
- **Architecture:** Conv1D → MaxPooling → Dropout → Flatten → Dense
- **Loss Function:** Categorical Crossentropy
- **Optimizer:** Adam

---

##  Dataset

- **Source:** MIT-BIH Arrhythmia Dataset *(or your dataset if different)*
- **Classes:** Normal, PVC, AFib, and more
- **Preprocessing:**
  - Normalization
  - Segmentation of beats
  - One-hot encoding of labels

---

##  How to Run

```bash
# Install dependencies
pip install numpy pandas scikit-learn matplotlib tensorflow

# Run the notebook
Open `ecg_1d_cnn.ipynb` in Google Colab or Jupyter Notebook
