# Bird Song Classification Project

## Overview
This project focuses on developing machine learning models to classify bird species based on their audio recordings. Utilizing deep learning techniques, the project explores various neural network architectures for accurate bird song identification.

## Features
- Multiple deep learning model architectures
- Audio preprocessing and feature extraction
- Mel log spectrogram generation
- Model training and evaluation
- Performance comparison across different neural networks

## Requirements
- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - librosa
  - scikit-learn
  - torch
  - scikit-image
  - seaborn
  - matplotlib
  - timm

## Dataset
The project uses the "Bird Songs Dataset" containing:
- Audio recordings of bird songs
- Metadata CSV file
- Multiple bird species

## Preprocessing Steps
1. Load audio files
2. Compute audio lengths
3. Resample audio to consistent sample rate
4. Generate Mel log spectrograms
5. Normalize spectrograms
6. Resize to standard input dimensions

## Models Compared
- DenseNet-121
- Xception
- ResNet-18
- ResNet-50

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC Score
- Confusion Matrix
- ROC Curves

## Usage
1. Install dependencies
2. Prepare your dataset
3. Run the Jupyter notebook/Python script
4. Analyze model performance

## Visualization
The project includes visualizations for:
- Training loss
- Confusion matrices
- ROC curves
- Audio length distribution

## Contributing
Contributions are welcome! Please submit pull requests or open issues.

## License
[Specify your license here]

## Acknowledgments
- Dataset providers
- Open-source library maintainers
