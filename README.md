# Brain Hemorrhage Image Metadata EDA
This project performs Exploratory Data Analysis (EDA) on a dataset of brain scan image metadata to identify key patterns related to image characteristics and class labels (hemorrhage vs normal).
##  Dataset
<ahref https://github.com/raseena123-a/Brain-Hemorrhage-Image-Metadata---EDA/tree/main</ahref>
##  Questions Explored
1. What is the distribution of brain hemorrhage vs normal cases?
2. Do image sizes (width, height) vary between hemorrhage and normal cases?
3. What are the most used image color modes?
4. What are the most frequent image sizes?
##  Visualizations
- Bar chart of class distribution
- Boxplots comparing image width and height between classes
- Bar chart of most used color modes
- Bar chart of top 10 image sizes
- ##  Key Insights
- The dataset contains a clear distribution of `hemorrhage` and `normal` classes.
- Most images use RGB mode, indicating they are in color.
- Image sizes are mostly consistent (e.g., 256x256), though some outliers exist.
- Tumor vs non-tumor images show slight variation in dimensions.
- ##  Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Google Colab
- ##  Conclusion
This exploratory data analysis provided insights into the structure and characteristics of brain scan image metadata used to detect hemorrhage conditions. Through analysis of 4,600 unique image records, we observed the following:
- The dataset includes two primary classes: `hemorrhage` and `normal`, with a balanced or slightly imbalanced distribution.
- Most images are stored in consistent formats and use the RGB color mode, which is suitable for computer vision applications.
- The majority of images share common dimensions (e.g., 256×256), simplifying preprocessing for modeling tasks.
- A few image entries differ in size or aspect ratio, indicating the potential need for resizing or normalization before model training.
- Hemorrhage and normal images show some variation in width and height distributions, suggesting slight structural differences that could aid classification.
These insights can inform preprocessing steps for deep learning, help identify potential data quality issues, and support the development of effective diagnostic models using medical imaging.



