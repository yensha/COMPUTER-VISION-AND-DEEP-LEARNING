# **COMPUTER-VISION-AND-DEEP-LEARNING**

## **Task 1: Computer Vision and Deep Learning - Homework 1**

### **Assignment Overview**
The homework consists of four main tasks implemented in a **single GUI**:
1. **Camera Calibration**
2. **Augmented Reality**
3. **Stereo Disparity Map**
4. **SIFT (Scale-Invariant Feature Transform)**
![Task1_GUI](https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%8716.png?raw=true)  
---

### **Camera Calibration**
#### **Objective:**
- Compute and display different camera calibration matrices and results.

#### **GUI Buttons & Functions:**
- **1.1 Find Corners:** Detect and draw corners on the chessboard images.
- **1.2 Find Intrinsic:** Compute and display the intrinsic matrix.
- **1.3 Find Extrinsic:** Compute and display the extrinsic matrix.
- **1.4 Find Distortion:** Compute and display the distortion matrix.
- **1.5 Show Undistorted Result:** Display both the distorted and undistorted images.

---

### **Augmented Reality**
#### **Objective:**
- Project words onto a chessboard in a specific orientation.
<img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%8711.png?raw=true" width="500">

#### **GUI Buttons & Functions:**
- **2.1 Show Words on Board:** Input a word and project it onto the chessboard horizontally.
- **2.2 Show Words Vertically:** Input a word and project it onto the chessboard vertically.
---

### **Stereo Disparity Map**
#### **Objective:**
- Generate and display a stereo disparity map from two rectified images.
- 
<img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%8712.png?raw=true" width="500">

#### **GUI Buttons & Functions:**
- **3.1 Load Image L:** Load the left image.
- **3.2 Load Image R:** Load the right image.
- **3.3 Compute Disparity Map:** Generate and display the disparity map.

---

### **SIFT (Feature Matching)**
#### **Objective:**
- Extract keypoints using SIFT and match them between two images.
  
<img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%8713.jpg?raw=true" width="100">  <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%8714.jpg?raw=true" width="100"> <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%8715.jpg?raw=true" width="200">

#### **GUI Buttons & Functions:**
- **4.1 Detect Keypoints:** Detect and display keypoints from an image.
- **4.2 Match Keypoints:** Match keypoints between two images and display the results.

---

## **Task 2: Computer Vision and Deep Learning - Homework 2**

### **Assignment Overview**
1. **Training a CIFAR10 Classifier Using VGG19 with Batch Normalization**
2. **Training a MNIST Generator Using DcGAN**

---

### **CIFAR10 Classifier (VGG19 + BN)**
#### **Objective:**
<img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%871.png?raw=true" width="600">

- Train a VGG19-based classifier for CIFAR10 dataset.

  <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/CIFAR%20-%20%E8%A4%87%E8%A3%BD.png?raw=true" width="200">
  
#### **GUI Buttons & Functions:**
- **1. Show Augmentation Images:** Load and display 9 augmented images.
 <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%872%20-%20%E8%A4%87%E8%A3%BD.png?raw=true" width="400">
- **2. Show Model Structure:** Display the structure of the VGG19 model.
 <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%874%20-%20%E8%A4%87%E8%A3%BD.png?raw=true" width="600">
- **3. Show Accuracy and Loss:** Display a graph of training/validation accuracy and loss.
 <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%873%20-%20%E8%A4%87%E8%A3%BD.png?raw=true" width="600">
- **4. Inference:** Load an image, run inference, and display the predicted class label and probability distribution.
 <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%875.png?raw=true" width="400">

---

### **MNIST Generator (DcGAN)**
#### **Objective:**
- Train a Deep Convolutional GAN (DcGAN) to generate handwritten digits.
  
<img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/Task2.png?raw=true" width="200"> <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%876.jpg?raw=true" width="200">
#### **GUI Buttons & Functions:**
- **1. Show Training Images:** Load and display the MNIST dataset with augmentation.
 <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%877.png?raw=true" width="600">
- **2. Show Model Structure:** Display the structure of the Generator and Discriminator models.
 <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%878.png?raw=true" width="600">
- **3. Show Training Loss:** Display a graph of the Generator and Discriminator loss.
 <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%879.png?raw=true" width="800">
- **4. Generate Images:** Generate and display fake images using the trained model.
 <img src="https://github.com/yensha/COMPUTER-VISION-AND-DEEP-LEARNING/blob/main/Img/%E5%9C%96%E7%89%8710.png?raw=true" width="600">

---

## **Summary**
This document outlines the functionalities required for both homework assignments. Each task involves implementing a **GUI with specific buttons**, handling **image processing, deep learning models, and visualization**.

---

