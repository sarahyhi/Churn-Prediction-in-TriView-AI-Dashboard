# Churn-Prediction-in-TriView-AI-Dashboard
**A Machine Learning and AI-Driven Dashboard for Predictive Insights**
Developed a dashboard combined with interactive data visualization, machine learning (ML) models for real-time churn prediction, and natural language generation (NLG) for automated dynamic reporting.

[Dataset Resource](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction/data)

### Final Dashboard:
![image](https://github.com/sarahyhi/Churn-Prediction-in-TriView-AI-Dashboard/blob/main/Dashboard 0506.png)

**Check My Project Presentation:** [Link](Presentation-final.pdf)

---

## Overview
This project focuses on developing a predictive analytics dashboard for customer churn using machine learning techniques integrated with Tableau through TabPy. The aim is to provide real-time insights into customer behavior and predict potential churn to facilitate proactive business decisions.

## Features
- **Predictive Modeling**: Utilizes various machine learning models, including Logistic Regression, Support Vector Classifier, Multilayer Perceptron, Random Forest, and Gradient Boosting, for churn prediction.
- **Data Visualization**: Interactive dashboards built with Tableau that provide real-time predictions, insights into key drivers, and actionable metrics.
- **Integration with TabPy**: Seamlessly integrates Python-based predictive analytics into Tableau for dynamic and real-time reporting.
- **Generative AI for Reporting**: Automatically generates insightful reports to summarize trends and predictions, streamlining communication with stakeholders.

### Project Workflow
1. **Data Preparation**
 - Data Cleaning and Analysis: Performed preprocessing tasks such as handling missing values, encoding categorical data, and normalizing features using Python libraries (*pandas, numpy*).
 - Exploratory Analysis: Identified key attributes influencing churn through visualization (*matplotlib, seaborn*) and feature engineering.
2. **Machine Learning**
 - Trained multiple models on structured data to evaluate predictive accuracy.
 - Selected the most suitable model based on performance metrics such as accuracy, precision, and recall.
3. **TabPy Setup**
 - Installed and configured TabPy for real-time model integration into Tableau.
 - Exported preprocessed datasets and model outputs for compatibility with Tableau’s requirements.
4. **Prediction and Visualization**
 - Deployed machine learning predictions in Tableau using TabPy.
 - Designed an interactive dashboard to display real-time predictions and visualize feature importance.
5. **Generative AI Extension**
 - Integrated a text-generation module to automate reporting, providing actionable insights based on prediction outcomes.

---

## Getting Started
### Prerequisites
- Python 3.x
- Tableau (with TabPy installed)
- Required Python libraries:
  - `pandas`
  - `scikit-learn`
  - `numpy`
  - `matplotlib`
  - `seaborn` 

### Installation for TabPy
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repo-name.git
   cd repo-name
   
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt

3. Set up TabPy server:
   ```bash
   tabpy
   
4. Open Tableau and connect to your TabPy server.

### Usage
1. Prepare your dataset.
2. Run the preprocessing and model training scripts to generate predictive models.
3. Load the preprocessed data and model predictions into Tableau.
4. Explore the interactive dashboard to gain insights and access automated reports.

### References
- **Tableau Workshop**: Learn How to Create and Share Data Visualizations. Available at: [Link](https://books.google.it/books?hl=zh-TW&lr=lang_en&id=JvPSEAAAQBAJ&oi=fnd&pg=PP1&dq=TabPy+machine+learning)
- **YouTube TabPy Tutorial**: [Link](https://www.youtube.com/watch?v=R__EeIePba8)
