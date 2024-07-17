# Defect-Detection-Breakpad

**Project Overview**
This project focuses on detecting and measuring holes in brake pads using image processing techniques. It employs template matching for hole detection, utilizes OpenCV contours to measure hole diameters, and implements a custom convolution function to determine edge distances. The primary goal is to automate and improve the accuracy of brake pad quality control.

**Features**
1. Hole Detection: Utilizes template matching to accurately count the number of holes in a brake pad.
2. Diameter Measurement: Leverages OpenCV contours to calculate the diameter of each detected hole.
3. Edge Distance Calculation: Implements a custom convolution function to identify distances between edges, ensuring precise measurement of hole positioning.

**Technologies Used**   
- Python
- OpenCV
- NumPy
  
**Installation**
1. Clone the repository:

git clone https://github.com/nirvana137/Defect-Detection-Breakpad.git
cd Defect-Detection-Breakpad

2. Install the required dependencies:
pip install -r requirements.txt
