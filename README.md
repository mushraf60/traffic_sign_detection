Traffic sign detection is a key task in autonomous driving and driver assistance systems. It involves locating and recognizing road signs from images or video streams using computer vision and deep learning techniques. This helps vehicles interpret road rules, improving safety and automation.

Tech Stack:
Python, OpenCV, NumPy
TensorFlow / PyTorch
Convolutional Neural Networks (CNNs)
   
Dataset: GTSRB - German Traffic Sign Recognition Benchmark (kaggle- https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)

 Project structure:
 
 ├── data/                   # GTSRB dataset
 
├── models/                 # Saved models

├── notebooks/              # Jupyter notebooks for exploration

├── src/

│   ├── dataset.py          # Dataset loading and preprocessing

│   ├── train.py            # Training script

│   ├── model.py            # CNN architecture

│   └── evaluate.py         # Evaluation metrics

├── requirements.txt

└── README.md

Future Work:

* Implement real-time detection using a webcam or dashcam feed.

* Add bounding box detection with models like YOLO or SSD.

* Improve robustness to poor lighting, motion blur, and occlusions.

* Deploy the model on edge devices using TensorFlow Lite.

* Expand to multilingual or region-specific sign datasets.

This project demonstrates a deep learning-based approach to traffic sign detection using the GTSRB dataset. By leveraging TensorFlow and CNNs, it achieves high accuracy in recognizing road signs, contributing to the development of safer and more reliable autonomous driving systems.
