
# Wheat Flour Iron Detection using Machine Learning 🧪🌾

This project uses machine learning to estimate and classify iron levels in wheat flour based on image data.


explored two different modeling approaches:

1. **Linear Regression Model**
   - Predicts iron concentration in PPM (parts per million)
   - Treats the task as a regression problem
   - Visualizes predicted vs actual PPM

2. **Random Forest Classifier**
   - Converts iron levels into 3 human-readable classes:  
     - Low (< 10 PPM), Medium (10–20 PPM), High (> 20 PPM)
   - Predicts class based on image data
   - Outputs confusion matrix, accuracy, and recall
## 🔧 Requirements

- Python 3.7+
- scikit-learn
- pandas
- numpy
- matplotlib
- PIL
