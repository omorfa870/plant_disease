🌿 Plant Disease Detection with CNNs in PyTorch
This project aims to identify and classify plant leaf diseases using Convolutional Neural Networks (CNNs). We fine-tune and compare several popular pre-trained CNN models—ResNet50, VGG-16, MobileNet-V2, and GoogleNet—to evaluate their performance on a real-world plant disease dataset.

📁 Dataset Overview
Source: Plant Disease Recognition Dataset on Kaggle

Path: /kaggle/input/plant-disease-dataset/Plant_Disease_Dataset

Classes:

Healthy

Powdery

Rust

Total Images: 1,532

🔀 Data Split
Training Set: 70%

Validation Set: 15%

Test Set: 15%

🧠 Model Architectures
We fine-tuned the following pre-trained CNN models from PyTorch’s model zoo:

🔹 ResNet50

🔹 VGG-16

🔹 MobileNet-V2

🔹 GoogleNet

Each model was adapted to classify the three plant leaf categories and evaluated on the same data splits for fair comparison.

🎯 Project Objectives
✅ Evaluate the performance of multiple CNN architectures on the same plant disease dataset.

✅ Understand the strengths and weaknesses of each model in the context of real-world leaf disease detection.

✅ Contribute to research in automated plant health monitoring using deep learning techniques.

🔬 Use Case
This study supports agricultural researchers and developers working on AI-driven plant disease diagnostics. With improved classification accuracy, farmers and agronomists can receive early warnings and take timely actions.

🛠️ Tools & Technologies
Framework: PyTorch

Models: Pre-trained CNNs (ResNet, VGG, etc.)

Platform: Kaggle Notebooks / Local environment

📌 Notes
All models were trained under the same conditions for fair evaluation.

This repository is maintained strictly for educational and research purposes.

