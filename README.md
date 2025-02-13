# ML-Assisted Alloy Design Using Wrought Aluminum Alloys

This repository contains the code and dataset used in the study:  
**"A feasibility study of machine learning-assisted alloy design using wrought aluminum alloys as an example"**  
by **Yasaman J. Soofi, Md Asad Rahman, Yijia Gu, and Jinling Liu.**

The study explores the application of **machine learning** to predict and analyze material properties, offering a data-driven approach to alloy design. It highlights the use of **advanced regression and classification models** to understand relationships between composition, processing, and resulting mechanical and technological properties.

[Read the published paper here.](https://www.sciencedirect.com/science/article/pii/S0927025622004943)

---

## Overview

This repository features Python code to perform **predictive modeling**, **feature analysis**, and **validation** of machine learning models, using datasets focused on wrought aluminum alloys. The project demonstrates the potential of ML techniques like **Random Forest, XGBoost, SVR**, and **ANN**, combined with advanced feature engineering and statistical validation, to enhance alloy design.

Key highlights include:
- Achieved an **8% improvement in prediction accuracy** (R² from 0.9 to 0.97) through hyperparameter tuning and advanced feature engineering.
- Expanded dataset size and improved model robustness using web scraping techniques (**BeautifulSoup, Selenium**).
- Validated model performance using **cross-validation**, **random seed testing**, and statistical methods (**t-tests**), with actionable insights from **feature importance analysis**.


 ![image](https://github.com/user-attachments/assets/4c83ad6c-ae90-4409-ab9d-f78519319c77)
Figure 2. Evaluation metrics of the developed ML models in predicting mechanical properties from compositions and tempers. a. The R2 metric of various ML models was developed for each of the six properties. The color bars show the average R2 from 100-seed experiments and the small bars show the variance. b. The R2 metric of RF models was developed for each of the six properties. c. The metric of Mean absolute percentage error (%) for RF models was developed for each of the six properties.


---

## Code Files

### Statistical Analysis
1. **`correlation_heatmap.ipynb`**  
   - Performs Spearman correlation analysis and generates a heatmap to visualize relationships between variables.

2. **`feature_importance.ipynb`**  
   - Analyzes feature importance for mechanical and technological properties. Produces figures showcasing the top-10 important features for each property.

### Predictive Modeling
3. **`100seeds_mechanical.ipynb`**  
   - Implements regression models (e.g., Random Forest, XGBoost, SVR) to predict mechanical properties, trained across 100 random seeds for robustness.

4. **`100seeds_technological.ipynb`**  
   - Implements classification models (e.g., Random Forest, ANN) to predict technological properties, trained across 100 random seeds.

### Validation and Visualization
5. **`LOOCV_scatterplt_mechanical.ipynb`**  
   - Trains and evaluates regression models using Leave-One-Out Cross-Validation (LOOCV) and generates scatter plots for mechanical property predictions.

6. **`LOOCV_technological.ipynb`**  
   - Trains and evaluates classification models using LOOCV for technological properties.

---

## Key Features
- **Supervised Learning**: Random Forest, XGBoost, SVR, ANN.
- **Web Scraping**: BeautifulSoup and Selenium for data collection from online repositories.
- **Data Preprocessing**: Ensured high data quality using Python libraries such as pandas and numpy.
- **Visualization**: Correlation heatmaps, feature importance plots, and scatter plots created using Matplotlib.

---

## Technologies Used
- **Programming Languages**: Python (pandas, numpy, scikit-learn, Matplotlib, TensorFlow).  
- **Statistical Methods**: Cross-validation, LOOCV, t-tests, and random seed testing.  
- **Machine Learning Frameworks**: scikit-learn, TensorFlow.  
- **Web Scraping**: BeautifulSoup, Selenium.

---

## Related Work

For further advancements in machine learning for alloy design, explore my subsequent project:  
[An Adaptive Physics-Based Feature Engineering Approach for Machine Learning-Assisted Alloy Design](https://github.com/yasamanjs/An-Adaptive-Physics-based-Feature-Engineering-Approach-for-Machine-Learning-assisted-Alloy-Disc).

---

## Citation

If you use this repository in your work, please cite:  
**"A feasibility study of machine learning-assisted alloy design using wrought aluminum alloys as an example"**  
by **Yasaman J. Soofi, Md Asad Rahman, Yijia Gu, and Jinling Liu**.  
[DOI Link](https://www.sciencedirect.com/science/article/pii/S0927025622004943)

---

