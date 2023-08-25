# Personal Protective Equipment (PPE) Detection Showcase

Welcome to the PPE Detection Showcase! This repository demonstrates the use of YOLO_NAS for detecting personal protective equipment (PPE) in images and videos. The model is trained to detect 7 classes of PPE items:

- Protective Helmet
- Shield
- Jacket
- Dust Mask
- Eye Wear
- Glove
- Protective Boots

## Getting Started

Before running the script, please ensure that you have selected the Run Time as GPU.

**Step 01: Install the Required Packages**

Run the following command to install the necessary packages:

Restart the Run Time after installing the packages.

**Step 02: Import Required Libraries**

Import the required libraries and modules.

**Step 03: Set Up Trainer**

Set up the checkpoint directory and instantiate the trainer.

**Step 04: Export Dataset from Roboflow**

Install and import the Roboflow package to download the dataset.

**Step 05: Load Dataset Parameters**

Define the dataset parameters in a dictionary.

**Step 06: Define Dataloaders**

Create dataloaders for training, validation, and testing.

**Step 07: Inspect Dataset Transforms**

Inspect the dataset transforms and modify them if needed.

**Step 08: Plot Augmented Training Data**

Plot a batch of training data with applied augmentations.

**Step 09: Instantiate the Model**

Instantiate the YOLO_NAS model for finetuning.

**Step 10: Define Training Parameters**

Define training parameters for your training run.

**Step 11: Download the Demo Videos**

Download demo videos for testing.

**Step 12: Train the Model**

Train the model using the defined trainer and parameters.

**Step 13: Get the Best Trained Model**

Retrieve the best trained model for evaluation.

**Step 14: Evaluate the Model on Test Set**

Evaluate the best trained model on the test dataset.

**Step 15: Predict with the Best Model**

Perform predictions using the best trained model on images.

**Step 16: Test on Video 1**

Test the model on a video and display the output.

**Step 17: Test on Video 2**

Test the model on another video and display the output.
