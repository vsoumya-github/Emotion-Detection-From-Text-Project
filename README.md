# Emotion Detection Using NLP and Deep Learning

This project is a beginner-friendly implementation of an emotion detection model using natural language processing (NLP) and deep learning techniques. It takes in user-input text and predicts the underlying emotion such as joy, sadness, anger, etc.

## 🔍 Overview

- **Goal:** Detect emotions from short text inputs.
- **Approach:** 
  - Preprocess user input (cleaning, tokenization, padding)
  - Train a neural network using TensorFlow and Keras
  - Predict emotions based on learned patterns
- **Tools Used:** 
  - Python  
  - Google Colab  
  - TensorFlow / Keras  
  - Gradio (for building the simple user interface)

## 🧠 Model Architecture

- Embedding Layer
- GlobalAveragePooling1D
- Dense Layers with ReLU activation
- Final Dense Layer for multiclass classification

The model was compiled using:
- **Loss Function:** SparseCategoricalCrossentropy  
- **Optimizer:** Adam  
- **Metric:** Accuracy

## 💻 How to Use

You can test the model using the Colab notebook and interact with it via a Gradio interface. Just type a sentence like:

```
"I'm feeling really happy today!"  
→ Output: joy
```

## 📁 Files Included

- `Emotion_Detection_Project.ipynb` — Complete Google Colab notebook with code, model, and UI
- `best_model.h5` — Saved trained model
- `README.md` — Project description (this file)

## 📌 Note

This project was built and tested in Google Colab. Dataset was imported from Kaggle using API within Colab.

## 🚧 Future Plans

- Improve emotion classification with a larger dataset
- Explore fine-tuning transformer models (e.g., BERT)
- Add confusion matrix and metrics visualization to notebook

## 🙋 Author Notes

This project was completed as part of my AI upskilling journey. I am currently exploring real-world NLP projects and deep learning models to strengthen my portfolio.
