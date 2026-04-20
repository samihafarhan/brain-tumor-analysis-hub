# Brain-Tumor-Analysis-Hub

> **A deep learning system for medical imaging that automates brain tumor segmentation and classification using T1 MRI scans.**

---

## Table of Contents
* [Overview](#overview)
* [Key Features](#key-features)
* [Quick Start](#quick-start)
* [Requirements](#requirements)
* [License](#license)

---

## Overview
This project uses AI to perform two tasks at once:

### 🧠 Segmentation
This part outlines tumor regions pixel-by-pixel, allowing for precise localization within the brain.

### 🏷️ Classification
This identifies the specific tumor type:
* **Glioma**
* **Meningioma**
* **Pituitary**
* **No Tumor**

---

## Key Features
* **Attention U-Net**: Uses attention gates to focus on the most important areas of the brain scans.
* **Flexible Training**: Supports separate training for each task or joint "multi-task" learning.
* **Evaluation**: Automatically tracks performance using **Dice Score** and **Accuracy**.

---

## Quick Start

### 1. Setup
Install the necessary tools using the command below:

```bash
pip install torch torchvision pandas scikit-learn 
```

### 2. Data
The project downloads the **BRISC 2025** dataset for you automatically. You do not need to do anything else.

### 3. Run
Open the **Jupyter notebook** and run the code to train the models and see your results.

---

## Requirements
* **Python**: 3.8 or newer
* **Computer**: A GPU (NVIDIA or Intel) is recommended to make the training faster.

## License
This project is licensed under the **MIT License**.
