# Enter-Week-1
I'm working on a deep learning model that classifies waste images into six categories: cardboard, glass, metal, paper, plastic, and trash.
🧾 Project Title: Garbage Classification using Transfer Learning
📌 Overview
This project focuses on building an image classification model that can automatically sort images of waste into six categories:

♻️ Cardboard

🥂 Glass

🛢️ Metal

🗞️ Paper

🥤 Plastic

🗑️ Trash

The goal is to support smart waste management systems by automating the sorting of garbage, enabling better recycling practices.

💡 Objective
To develop a deep learning model that:

Takes an image of a waste item as input

Predicts which of the 6 categories it belongs to

Is trained using Transfer Learning (EfficientNetV2B2)

Uses data augmentation, learning rate scheduling, and fine-tuning to boost performance

Will be deployed online using Hugging Face Spaces

🧠 Technologies Used
Python

TensorFlow / Keras

EfficientNetV2B2 (Transfer Learning)

Google Colab

Matplotlib (for visualization)

Hugging Face (for deployment)

📂 Dataset
We used a version of the TrashNet dataset, which contains labeled images of real waste materials across six classes. The dataset was resized for easier training and loaded from a GitHub source.

Class	Number of Images
Cardboard	~400
Glass	~500
Metal	~400
Paper	~600
Plastic	~480
Trash	~130

⚙️ Model Architecture
Base: EfficientNetV2B2 pretrained on ImageNet

Custom Layers:

Global Average Pooling

Dense Layer (ReLU)

Dropout (to prevent overfitting)

Final Dense Layer with Softmax (6 outputs)

📈 Improvements Implemented
✅ Data Augmentation

✅ Learning Rate Scheduling

✅ Fine-tuning Pretrained Weights

✅ Model Evaluation and Visualization

✅ Deployment on Hugging Face Spaces

🚀 Outcome
The final model demonstrates significant learning improvements over baseline, showing increased training stability and generalization using advanced training strategies. It's suitable for real-world prototyping in smart bins, recycling plants, and environmental monitoring applications.
