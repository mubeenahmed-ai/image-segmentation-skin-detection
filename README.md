# Unsupervised Image Segmentation and Probabilistic Skin Detection

This project implements fundamental computer vision and machine learning techniques to perform semantic image segmentation and pixel-wise classification. It focuses on the comparison of clustering algorithms and the development of a probabilistic model for skin detection.

## Project Highlights
* **Unsupervised Clustering:** Implementation and benchmarking of K-Means and K-Medoids for segmenting high-resolution images into distinct semantic regions.
* **Probabilistic Modeling:** Development of a skin detection classifier using Likelihood Ratio Testing (LRT) and probability density estimation.
* **Feature Engineering:** Analysis of color spaces, specifically the conversion from RGB to YCbCr to improve model robustness against lighting variations.
* **Dimensionality Reduction:** Application of PCA and t-SNE to visualize and verify the separability of high-dimensional pixel data.

##  Tech Stack
* **Language:** Python
* **Libraries:** NumPy, OpenCV (cv2), Scikit-learn, Matplotlib, PIL
* **Techniques:** K-Means, K-Medoids, PCA, t-SNE, Likelihood Ratio Test, YCbCr Color Analysis.

## Project Structure
* `image-segmentation-skin-detection.ipynb`: The primary technical report containing the implementation, mathematical derivations, and visualizations.
