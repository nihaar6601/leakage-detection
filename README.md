# Wall and Roof Leakage Detection Using Computer Vision

### Project Overview:

This project focuses on detecting water leakage in walls and roofs using computer vision and machine learning techniques. The system analyzes images of surfaces to identify leakage areas and provides automated reports of leakage instances.

### Key Components:

1. Data Preprocessing

 - Image Resizing – Standardized all images for consistent feature extraction

 - Grayscale Conversion – Simplified images to focus on texture patterns

 - Normalization and Dimensionality Reduction – Reduced computational load and improved model performance

2. Feature Extraction

 - Local Binary Pattern (LBP):
   - Captured texture details for surface analysis

 - Gray-Level Co-occurrence Matrix (GLCM):
   - Extracted statistical features related to texture and pixel relationships

3. Classification

 - Four machine learning classifiers were used for detection:

   - Random Forest	
   - Support Vector Machine 
   - XGBoost	
   - K-Nearest Neighbor

 - Random Forest classfier resulted in highest accuracy of 97%

### Technologies Used:

 - Python

 - OpenCV – For image preprocessing and feature extraction

 - Scikit-learn & XGBoost – For machine learning models

### Features:

 - Automated detection of wall and roof leakage from images

 - Texture-based feature extraction using LBP and GLCM

 - Performance evaluation using accuracy, precision, recall, and F1 score

