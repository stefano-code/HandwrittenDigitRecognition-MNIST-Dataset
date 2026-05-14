# ✍️ Handwritten Digit Recognition - MLP with Keras

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-2.x-red.svg)](https://keras.io/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A deep learning project that recognizes handwritten digits (0-9) using a **Multilayer Perceptron (MLP)** neural network. The model is trained on the classic MNIST dataset and exported to **TensorFlow Lite** format for mobile deployment, both in its **normal** and **quantized** form.

## 🎯 Key Features

- ✅ Multi-class classification (10 digits: 0-9)
- ✅ MLP architecture with one hidden layer
- ✅ Training accuracy: **~98.9%**
- ✅ Test accuracy: **~98.0%**
- ✅ Export to TensorFlow Lite (.tflite)
- ✅ Quantized model for edge devices
- ✅ Ready for Android/iOS deployment

## 🧠 Model Architecture
- Input Layer: 784 neurons (28×28 pixels flattened)
- Hidden Layer: 512 neurons (ReLU activation)
- Output Layer: 10 neurons (Softmax activation)

- ### Model Statistics
- **Total parameters**: 407,050
- **Trainable parameters**: 407,050
- **Input shape**: (784,) column vector
- **Output shape**: (10,) probability distribution

## 📊 Dataset

The project uses the **MNIST dataset** (Modified National Institute of Standards and Technology), which is available directly through Keras.

| Dataset | Samples | Image Size | Labels |
|---------|---------|------------|---------|
| Training | 60,000 | 28×28 pixels | 0-9 |
| Test | 10,000 | 28×28 pixels | 0-9 |



