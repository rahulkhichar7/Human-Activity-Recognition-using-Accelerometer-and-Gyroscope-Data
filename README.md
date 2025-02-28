# Human Activity Recognition using AI and ML

## Overview
This project focuses on classifying human activities using the UCI HAR dataset. It compares traditional machine learning models with deep learning approaches to determine the most effective method for accurate recognition.

## Approach
- **Data Preprocessing**: Standardized the dataset for optimal model performance.
- **Machine Learning Models**: Implemented Logistic Regression, Decision Trees, Random Forest, and SVM. Logistic Regression (96.09%) and SVM (95.21%) performed best.
- **Deep Learning Models**: Trained 1D CNN and LSTM models, where CNN outperformed LSTM (88.26% vs. 62.95%).
- **Feature Engineering**: Used TSFEL for feature extraction but observed a drop in accuracy compared to the original dataset.

## Observations
- Machine learning models performed better than deep learning on structured features.
- CNN excelled in identifying patterns from raw data.
- TSFEL-generated features did not improve results.

## Future Work
- Optimize deep learning models for better generalization.
- Explore hybrid approaches combining ML and DL.
- Experiment with different feature extraction techniques.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/rahulkhichar7/Human-Activity-Recognition-using-Accelerometer-and-Gyroscope-Data.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Model:
   ```bash
    model.ipynb
   ```

## License
This project is open-source 

