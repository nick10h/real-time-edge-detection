# Real-Time Edge Detection

## Overview
This project implements real-time edge detection using OpenCV and Python. It processes live video streams, applying various edge detection techniques such as Canny, Sobel, and Laplacian filters to highlight object boundaries in real-time.

## Features
- Real-time edge detection on live video feeds.
- Multiple edge detection techniques:
  - **Canny Edge Detection**
  - **Sobel Operator**
  - **Laplacian Operator**
- Adjustable parameters for fine-tuning edge detection.
- Optimized performance for smooth video processing.

## Technologies Used
- **Python** - Programming language
- **OpenCV** - Image processing and computer vision library
- **NumPy** - Array processing for image manipulation
- **Tkinter (if used)** - GUI for parameter tuning

## Installation
Ensure you have Python installed (preferably 3.x). Then, install the required dependencies:

```sh
pip install opencv-python numpy
```

## Usage
Run the script to start real-time edge detection:

```sh
python edge_detection.py
```

### Keyboard Controls (if implemented):
- Press `Q` to quit the application.
- Use UI sliders (if available) to adjust parameters.

## Edge Detection Techniques
### 1. Canny Edge Detection
Applies Gaussian blur followed by gradient calculations to detect strong edges.

### 2. Sobel Operator
Computes gradients in horizontal and vertical directions to highlight edges.

### 3. Laplacian Operator
Uses second-order derivatives to detect edges more prominently.


## Future Enhancements
- Add more edge detection techniques.
- Implement GUI for real-time parameter tuning.
- Support video file input instead of just webcam.

