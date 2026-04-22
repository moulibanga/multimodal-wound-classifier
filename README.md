# Multimodal Wound Classification (ResNet50)

## Overview
This project builds a deep learning model to classify wound types using medical images. The model is based on a pretrained ResNet50 architecture and was trained on a dataset of 730+ wound images.

## Problem
Accurate wound classification is important for clinical decision-making, but can be challenging due to visual variability across wound types.

## Approach
- Used ResNet50 (pretrained on ImageNet)
- Fine-tuned for multiclass wound classification
- Dataset split into training, validation, and test sets
- Models were originally trained separately on left and right leg datasets

## Results
- ResNet50 achieved ~90% classification accuracy
- Performance evaluated using:
  - Accuracy
  - Precision / Recall / F1-score
  - Confusion Matrix

## Files
- `wound_classification_pipeline.ipynb` — main training + evaluation pipeline
- `paper.pdf` — full research paper with detailed methodology and results

## Notes
This repository contains a representative pipeline for the best-performing model. The original research workflow included multiple experiments and dataset partitions.

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib
