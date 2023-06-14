# Deep Learning Model to Detect Animals

This repository contains a deep learning model that can identify and predict 80 different varieties of animals. The model has been trained using the dataset available at [Kaggle](https://www.kaggle.com/datasets/antoreepjana/animals-detection-images-dataset).

## Model Details

- This model is capable of detecting and predicting 80 different varieties of animals.
- The model has been developed using deep learning techniques.
- It has been trained on a dataset consisting of images of various animals.


## Model Architecture

- The model architecture used in this project is the VGG-16 architecture.
- The VGG-16 architecture is a widely-used convolutional neural network architecture known for its excellent performance in image classification tasks.

## Model Accuracy

- The model has achieved a training accuracy of 90% on the training set.

## Repository Contents

- `animal_detection_model.ipynb`: Jupyter Notebook containing the code for training and evaluating the model.
- `model_checkpoints/`: Directory containing saved checkpoints of the trained model.
- `animal_detection.py`: Python script for using the trained model to predict the animal in an input image.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/vishnugamini/Deep-learning-model-to-detect-animals.git
   
2. Install the required dependencies if needed.

3. Place the input image you want to predict in the repository directory.

4. Run the animal_detection.py script:
   ```bash
   python animal_detection.py --image_path <path_to_input_image>
  The script will load the trained model from the saved checkpoint and predict the animal in the input image.
  Feel free to explore and utilize the model for animal detection!
