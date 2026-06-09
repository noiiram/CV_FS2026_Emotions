# Facial Expression Recognition: Emotion Classification
**HSLU Computer Vision | 2026**

## Project Overview
This project investigates facial expression recognition (FER) on the FER-2013 dataset 
using two approaches: supervised fine-tuning of a ResNet18 backbone and zero-shot 
classification with CLIP (ViT-B/32).

## Dataset
FER-2013 — downloaded via Kaggle API.  
https://www.kaggle.com/datasets/msambare/fer2013

## Requirements
- Python 3.10+
- PyTorch
- torchvision
- CLIP (`pip install git+https://github.com/openai/CLIP.git`)
- OpenCV
- scikit-learn
- matplotlib, seaborn

## How to Run
1. Open `Notebook_Emotion_classification_Bernasconi_Stutz.ipynb` in Google Colab
2. Add your Kaggle API token in the setup cell
3. Run all cells top to bottom
