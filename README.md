# Vaishalini_R-Comsys_hackathon
# COMSYS-HACKATHON--ai-enabled-accident-detection-system
description:
An accident Detection System is designed to detect accidents via video or CCTV footage. Many people lose their lives in road accidents. We can minimize this issue by using CCTV accident detection. This repository majorly explores how CCTV can detect these accidents with the help of Deep Learning.

Prerequisites:
- To use this project Python Version > 3.6 is recommended.
- To contribute to this project, knowledge of basic python scripting, Machine Learning, and Deep Learning will help.

This project includes 4 things.

1. data: Kaggle dataset on [Accident Detection from CCTV footage](https://www.kaggle.com/code/mrcruise/accident-classification/data).
2. accident-classification.ipynb: This is a jupyter notebook that generates a model to classify the above data. This file generates two important files model.json and model_weights.h5.
3. detection.py: This file loads the Accident Detection system with the help of model.json and model_weights.h5 files.
4. camera.py: It packs the camera and executes the detection.py file on the video dividing it frame by frame and displaying the percentage of the prediction in the accident (if present) in the frame.
