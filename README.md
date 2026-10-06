# Water-Quality-Aquaculture-Suitability-Prediction
Random Forest model for predicting aquaculture suitability based on water quality parameters, with EDA, data preprocessing, model evaluation, and feature importance analysis.

1. Collected and analyzed water quality data containing 4,300 records and 21 columns with different physical and chemical water parameters.
2. Analyzed important water parameters such as temperature, turbidity, dissolved oxygen, pH, ammonia, nitrite, phosphorus, hardness, alkalinity, and other measurements.
3. Performed Exploratory Data Analysis (EDA) to understand the distribution and relationships between different water quality parameters.
4. Used Water Quality Index (WQI) as an important indicator for evaluating overall water quality.
5. Analyzed aquaculture suitability classifications such as Highly Suitable, Suitable, Restricted/Stressed, and Unsuitable/Critical.
6. Used Python libraries including Pandas, NumPy, Matplotlib, and Seaborn for data processing and visualization.
7. Applied Label Encoding to convert categorical classification values into numerical values suitable for machine learning.
8. Split the dataset into training and testing sets using train_test_split to evaluate the machine learning model.
9. Built a Random Forest Classifier to classify water quality and predict its suitability based on the available water parameters.
10. Evaluated the model using Accuracy Score, Classification Report, and Confusion Matrix, helping assess how effectively the model classifies different water-quality categories.
