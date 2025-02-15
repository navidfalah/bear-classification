# Bear Classifier with FastAI 🐻🤖

This project demonstrates **image classification** using the **FastAI** library to classify images of bears into three categories: **grizzly**, **black**, and **teddy**. The goal is to build a model that can accurately identify the type of bear in an image. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **FastAI** to build and train a convolutional neural network (CNN) for image classification. 🤖📸
- Leverages the **ResNet18** architecture for transfer learning. 🧠🔍
- Implements data augmentation, model training, and evaluation. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install fastai bing-image-downloader ipywidgets
```

---

## Usage 🖥️

1. **Download Dataset**: The script downloads images of grizzly, black, and teddy bears using the Bing Image Downloader.
2. **Preprocess Data**: Applies data augmentation and splits the data into training and validation sets.
3. **Build Model**: Defines and trains a ResNet18 model using transfer learning.
4. **Evaluate Model**: Evaluates the model's performance using accuracy and confusion matrices.
5. **Interactive Interface**: Provides an interactive interface to upload and classify bear images.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Downloads and organizes bear images into categories.
  - Applies data augmentation and normalization.

- **Model Definition**:
  - Uses a pre-trained ResNet18 model for transfer learning.
  - Adds a custom classification head for bear classification.

- **Training**:
  - Trains the model using the training set.
  - Tracks training and validation accuracy.

- **Evaluation**:
  - Evaluates the model's performance on the validation set.
  - Visualizes results using confusion matrices and top losses.

- **Interactive Interface**:
  - Provides an interface to upload and classify bear images.

---

## Results 📊

- **Training/Validation Accuracy**: The model achieves high accuracy on the training and validation sets.
- **Confusion Matrix**: Visualizes the model's predictions against actual labels.
- **Interactive Classification**: Allows users to upload images and get predictions.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Epoch 1/4: train_loss=0.123, valid_loss=0.045, error_rate=0.02
Epoch 2/4: train_loss=0.045, valid_loss=0.032, error_rate=0.01
```

---

## Dependencies 📦

- `fastai`
- `bing-image-downloader`
- `ipywidgets`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
