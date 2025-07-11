# 📚 Digital Image Processing Coursework

This repository contains solutions to **Digital Image Processing (DIP)** lab assignments. Each assignment is implemented in **Python** using **OpenCV**, and organized into separate folders. All relevant images used for processing are stored in an `images` subdirectory inside each assignment folder.

## 🗂 Repository Structure

```
DIP-Coursework/
├── A1/
│   ├── CS22B1082_Assignment1.ipynb
│   └── images/
├── A2/
│   ├──  CS22B1082_Assignment2.ipynb
│   └── images/
├── A3/
│   ├──  CS22B1082.ipynb
│   └── images/
├── A4/
│   ├──  CS22B1082_Assignment4.ipynb
│   └── images/
├── A5/
│   ├──  CS22B1082_Assignment5.ipynb
│   └── images/
└── README.md
```

---

## 🔍 Assignment Details

### 📁 A1: PSNR without Built-in Function

* Compare quality of a degraded face image with the original.
* Steps:

  * Apply blur, Gaussian noise, and JPEG 2000 compression (\~70–80% quality).
  * Compute PSNR manually (without using built-in function).

---

### 📁 A2: Grayscale Conversion and Image Resizing

* Convert color image to grayscale:

  * By averaging RGB values (manual)
  * Using built-in functions
* Resize grayscale image by factor of 2 using:

  * Nearest Neighbor (manual & built-in)
  * Bilinear Interpolation (manual & built-in)
  * Bicubic Interpolation (built-in)

---

### 📁 A3: Rotation and Angle Estimation

* Rotate image of Leaning Tower of Pisa to estimate inclination angle:

  * Implement rotation using:

    * Manual bilinear interpolation
    * OpenCV's built-in functions

---

### 📁 A4: Histogram Equalization & Matching

* Perform histogram equalization on `pout-dark`.
* Match histogram of `pout-dark` with `pout-bright` using:

  * User-defined methods
  * Built-in OpenCV functions

---

### 📁 A5: Advanced Image Processing Task

* Problem statement specific to assignment (details in notebook).
* Includes implementation and output.

---

## ⚙️ Technologies Used

* Python 3.x
* Jupyter Notebooks (`.ipynb`)
* OpenCV (`cv2`)
* NumPy
* Matplotlib (for visualizations)

---

## 📌 Notes

* All image processing tasks prioritize manual implementation over built-in functions unless specified.
* Each assignment folder includes:

  * A Jupyter notebook with code and explanations.
  * An `images/` folder with input images.

---
