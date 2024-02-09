# McDonald's Fast Food Customer Segmentation and Profiling

## Overview
This project analyzes customer preferences and behaviors in the context of McDonald's fast-food data. By employing machine learning techniques and exploratory data analysis, we aim to identify distinct customer segments, profile them, and provide insights for targeted marketing strategies.

## Dataset
The dataset comprises various attributes related to customer preferences, such as taste preferences, perceived healthiness, and visit frequency. The data has been preprocessed and transformed for analysis.

## Analysis Steps

### 1. Data Exploration and Preprocessing
- 📊 Imported necessary libraries (NumPy, Pandas, Matplotlib, Seaborn).
- 📁 Loaded the McDonald's dataset and inspected its structure.
- ❌ Checked for missing values (none found) and performed basic data statistics.

### 2. Customer Segmentation
- 🎯 Applied K-Means clustering to identify distinct customer segments based on their responses to taste preferences.
- 📈 Determined the optimal number of clusters using the Elbow Method.
- 🌐 Visualized customer segments in a 2D PCA space.
- 🏷️ Assigned cluster labels to the original dataset.

### 3. Segment Profiling
- 📋 Described each customer segment based on their Like ratings for McDonald's food items.
- 👤 Analyzed the gender distribution within each segment.
- 📊 Examined the average age and visit frequency for each identified segment.

### 4. Target Segment Selection
- 🔄 Transformed categorical variables (VisitFrequency, Like, Gender) into numerical representations.
- 📊 Calculated and visualized the average visit frequency and Like ratings for each customer segment.
- 🎯 Selected the target segment based on preferences and behaviors.

## Results and Insights
The analysis identified four distinct customer segments with unique preferences and behaviors. The selected target segment exhibits specific characteristics that can be leveraged for tailored marketing strategies.

🔍 Feel free to explore the code, visualizations, and insights provided in this repository. For any questions or further analysis, please refer to the Jupyter notebook or script.

**Note:** This project is for educational and analytical purposes, utilizing synthetic McDonald's fast-food data.

