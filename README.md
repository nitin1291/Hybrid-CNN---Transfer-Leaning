# Transfer Learning for Image Classification - Hybrid Model

## Overview

MSc dissertation project investigating hybrid CNN models for image classification through transfer learning. This research combines features from multiple pre-trained networks (MobileNetV2, ResNet50, VGG16) using an attention-based fusion mechanism to improve classification accuracy while maintaining computational efficiency.

## Key Features

- Hybrid CNN architecture with transformer-inspired attention mechanisms
- Multi-branch attention model and optimized fine-tuned dual-branch model
- Performance evaluation on the Stanford Dogs Dataset (fine-grained classification)
- Comprehensive evaluation metrics including accuracy, precision, recall, F1-score, and inference time

## Results

- Multi-branch hybrid model: 76.13% accuracy (+1.92% over best baseline)
- Fine-tuned hybrid model: 74.96% accuracy with improved inference time
- Successful feature fusion even with varying individual model performances

## Requirements

- Python 3.7+
- TensorFlow 2.x
- Keras API
- Google Colab (for GPU/TPU acceleration)

## Author

Nitin Mundakkil, MSc Data Science & Computational Intelligence, Coventry University, 2025
