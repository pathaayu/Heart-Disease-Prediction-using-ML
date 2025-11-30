# Heart-Disease-Prediction-using-ML
Here is a polished, professional **README.md** for your **Heart Diseases Prediction Project** based on the info you provided.
It’s structured to highlight your skills, data, models, and results—perfect for a GitHub portfolio!

---

````markdown
# Heart Disease Prediction Using Machine Learning in Python

![Python Logo](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-0.24-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## Project Overview

This project aims to predict the presence of heart disease using supervised machine learning techniques applied to health and lifestyle data.  
The dataset contains multiple personal health indicators such as BMI, smoking habits, stroke history, physical and mental health status, walking difficulties, and demographic factors.

The goal is to build an accurate, interpretable model using **Decision Tree classifiers** to identify individuals at risk of heart disease, enabling early intervention and awareness.

---

## Dataset

The data is provided in CSV format with the following columns:

| Column Name       | Description                              |
|-------------------|------------------------------------------|
| HeartDisease      | Target variable: Presence of heart disease (Yes/No) |
| BMI               | Body Mass Index                         |
| Smoking           | Smoking status (Yes/No)                 |
| AlcoholDrinking   | Alcohol consumption (Yes/No)            |
| Stroke            | History of stroke (Yes/No)              |
| PhysicalHealth    | Number of days physical health was not good in last month |
| MentalHealth      | Number of days mental health was not good in last month  |
| DiffWalking      | Difficulty walking (Yes/No)              |
| Sex               | Gender (Male/Female)                    |
| AgeCategory       | Age group                              |
| Race              | Race/Ethnicity                        |
| Diabetic          | Diabetes status (Yes/No)                |
| PhysicalActivity  | Physical activity status (Yes/No)       |
| GenHealth         | General health rating                   |
| SleepTime         | Average hours of sleep per day          |
| Asthma            | Asthma diagnosis (Yes/No)               |
| KidneyDisease     | Kidney disease diagnosis (Yes/No)       |
| SkinCancer        | Skin cancer diagnosis (Yes/No)          |

---

## Key Libraries & Tools

- Python 3.x  
- Pandas & NumPy (Data manipulation)  
- Scikit-learn (Machine Learning)  
- Matplotlib / Seaborn (Data visualization)  
- Jupyter Notebook (Project development)

---

## Methodology

1. **Data Cleaning and Preprocessing**  
   - Handling missing values and encoding categorical variables  
   - Feature scaling and transformation as needed  

2. **Exploratory Data Analysis (EDA)**  
   - Visualizing distributions and relationships between features  
   - Correlation analysis to select important variables  

3. **Model Training**  
   - Splitting data into training and testing sets  
   - Training Decision Tree classifier with `criterion='entropy'` and tuning parameters  
   - Evaluating model performance with accuracy, confusion matrix, and classification report  

4. **Model Interpretation**  
   - Plotting decision tree visualizations for interpretability  
   - Analyzing feature importance to understand drivers of heart disease risk  

---

## Usage

To run the project locally:

```bash
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
pip install -r requirements.txt  # pandas, numpy, scikit-learn, matplotlib, seaborn
jupyter notebook
````

Open the notebook `HeartDiseasePrediction.ipynb` and run cells step-by-step to explore the analysis and model building.

---

## Results

* Decision Tree classifier achieved **91%** accuracy on the test set.
* Key predictive features included **AgeCategory, DiffWalking, Stroke history, Diabetes, and BMI**.
* Visualizations reveal how combinations of lifestyle and health factors impact disease risk.

---

## Future Work

* Test additional algorithms such as Random Forest, XGBoost, or Logistic Regression
* Apply hyperparameter tuning and cross-validation for improved performance
* Incorporate more detailed patient medical histories and lifestyle factors
* Build an interactive dashboard for non-technical stakeholders

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## Contact

Created by **Aayushi Pathak** — pathakaayushi1@gmail.com
LinkedIn: 
GitHub: [github.com/yourusername](https://github.com/yourusername)

---

*Feel free to reach out for collaboration or questions!*

```

---

If you want, I can also help with:  
- A requirements.txt file  
- Example notebook templates  
- Adding badges or GIFs to README  
- Detailed project folder structure  

Just ask!
```
