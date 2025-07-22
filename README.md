# 🎙️ Emotion Recognition from Speech using RNNs

This project implements a deep learning-based system to recognize emotions from speech using Recurrent Neural Network (RNN) architectures such as LSTM and Bi-directional LSTM. The model classifies audio inputs into 8 distinct emotions using the RAVDESS dataset.

---

## Overview

- Extracted audio features: **MFCCs**, **Chroma**, **Spectral Contrast**, **RMS Energy**, and **Zero-Crossing Rate**
- Applied audio augmentation techniques: `pitch shift`, `time stretch`, `bandpass filtering`, `noise addition` to improve model generalization
- Trained and evaluated four RNN-based models:
  - Single-layer LSTM
  - Two-layer LSTM
  - Single-layer Bi-LSTM
  - Two-layer Bi-LSTM
- Achieved **67% accuracy** using the **2-layer Bi-LSTM**, outperforming the baseline LSTM by 7%
- Integrated the best-performing model into a simple real-time emotion prediction interface

---

## Tech Stack

- **Language**: Python  
- **Libraries**: TensorFlow, Keras, NumPy, pandas, Matplotlib  
- **Platform**: Google Colab (GPU-enabled)

---

## Evaluation

- **Metrics Used**: Accuracy, Precision, Recall, F1-Score
- **Visuals**: Confusion Matrices, Accuracy vs Epoch Plots

---

## Key Features

- Robust feature extraction pipeline for emotion detection
- Dataset augmentation to improve performance and generalization
- Comparative analysis across LSTM and Bi-LSTM architectures
- End-to-end pipeline from training to real-time prediction

---

## Dataset

- [RAVDESS Dataset](https://zenodo.org/record/1188976)  
  A validated multimodal dataset with 24 actors performing 8 emotions.

---

## Future Work

- Explore transformer-based models for improved performance
- Extend to multilingual emotion recognition

