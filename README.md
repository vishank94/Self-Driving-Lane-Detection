# Table of Contents
1. [Introduction](README.md#introduction)
2. [Approach](README.md#approach)
3. [Dependencies](README.md#dependencies)
4. [Running the Code](README.md#running-the-code)
5. [Directory Structure](README.md#directory-structure)


# Introduction

This repository contains solution to coding challenge lane detection for self driving cars.


# Approach

1. Some basic image processing concepts used here are - Color Selection, RoI Selection, Grayscaling, Gaussian Smoothing.
2. Other concepts used specifically for lane line detection include - Canny Edge Detection, Hough Tranform Line Detection.
4. The notebook uses all of the above techinques to detect lane lines of different types and colors from a video of the road.
5. The pipeline used here - image processing->edge detection and extrapolation->overlay detection on original image.


# Dependencies
Python libraries: opencv, pandas, numpy, matplotlib


# Running the Code
1. Jupyter notebook LaneDetection.ipynb (Python kernel) is the master file.
2. It makes use of:
  - solidWhiteCurve.jpg
  - challenge.mp4
3. The repository directory structure given below must be maintained for the code to run successfully.


# Directory Structure
The directory structure for this repository is as follows:
    
    ├── README.md 
    ├── Scripts
        └── LaneDetection.ipynb
