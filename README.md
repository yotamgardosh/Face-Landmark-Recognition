# Facial Landmark Detection Project
This project is aimed at developing a deep learning model for facial landmark detection using the iBUG 300W Large Face Landmark dataset. The model is based on a modified ResNet-18 architecture and is trained to predict the coordinates of 68 facial landmarks.

## Features
* Neural Network Model: Utilizes a modified ResNet-18 architecture for facial landmark detection.
* Data Augmentation: Includes image transformation techniques to enhance the training dataset.
* Training and Validation Pipeline: Implements functions for training and validating the model.
  
## How to Use
1. Clone the Repository: Clone this repository to your local machine using the following command:
  ```bash
  git clone https://github.com/yourusername/facial-landmark-detection.git
```

2. Install Dependencies: Make sure you have the required dependencies installed. You can install them using pip:
  ```bash
  pip install -r requirements.txt
```
3. Download Dataset: Download the iBUG 300W Large Face Landmark dataset and place it in the appropriate directory (ibug_300W_large_face_landmark_dataset).

4. Training: Run the train_and_validate_model function to train the neural network model. Adjust the hyperparameters as needed.

5. Evaluation: Visualize the model's predictions on the validation dataset using the show_examples function.

## Requirements
Python 3.x
PyTorch
torchvision
Matplotlib
NumPy
OpenCV

## Contributors
Yotam Gardosh

## License
This project is licensed under the MIT License - see the LICENSE file for details.
