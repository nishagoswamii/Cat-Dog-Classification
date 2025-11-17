# Cat & Dog Classification

A computer vision project that classifies images of cats and dogs using Convolutional Neural Networks (CNNs) with TensorFlow and Keras.

## Overview

This repository contains an end-to-end solution for binary image classification using deep learning. The model is trained on a balanced dataset to distinguish between cats and dogs.

## Dataset

- **Source**: The `cats_and_dogs_filtered` dataset from Kaggle
- **Structure**:
  - `train/cats` - 1000 training images
  - `train/dogs` - 1000 training images
  - `validation/cats` - 500 validation images
  - `validation/dogs` - 500 validation images

> **Note**: Adjust the `PATH` variable in the notebook to point to your local dataset directory.

## Features

- Data loading and preprocessing using `ImageDataGenerator`
- Real-time data augmentation (rescaling, shearing, zooming, flipping)
- Custom CNN built with `tf.keras.Sequential`
- Training visualizations (accuracy and loss plots)
- Model inference pipeline

## Tech Stack

- Python 3.8+
- TensorFlow 2.x with Keras API
- OpenCV
- Matplotlib
- NumPy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nishagoswamii/Cat-Dog-Classification.git
   cd Cat-Dog-Classification
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate      # Linux/Mac
   venv\Scripts\activate          # Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Cat-Dog-Classification.ipynb
   ```

2. Update the dataset path in the notebook to match your local directory

3. Run all cells to train the model and generate visualizations

## Results

- Training Accuracy: ~93%
- Validation Accuracy: ~90%

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
