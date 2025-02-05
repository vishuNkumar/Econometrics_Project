# Econometrics_Project
Heart Disease Analysis Report by SPSS
## 1. About Heart Disease
The report investigates heart disease by analyzing biological and lifestyle factors, emphasizing variables such as age, cholesterol levels, and chest pain. The key objective is to identify factors that predict the likelihood of heart disease and assess their hierarchy of influence.

- Key findings highlight the significance of certain factors:
  - Chest pain (cp) is identified as the most impactful predictor.
  - Other critical variables include the number of major vessels (caa), maximum heart rate (thalachh), exercise-induced angina (oldpeak), and thalassemia (thall).
## 2. Survey Overview
The dataset contains information on 303 individuals, with no missing values. It includes demographic, clinical, and lifestyle-related variables to facilitate comprehensive analysis:

 - **Variables**: Age, gender, chest pain, cholesterol levels, exercise stress, and others.
 - **Purpose**: Explore correlations between these factors and heart disease risk.
 - **Hypothesis**:
    - Null hypothesis (H₀): Independent factors do not significantly explain the risk of heart disease.
    - Alternative hypothesis (H₁): At least one predictor has a significant influence.
      ![Image](https://github.com/user-attachments/assets/32984c4a-6fb6-4ba1-b406-d01344ec8c1b)
## 3. Key Research Problems:
 - **Exploring Effects of Lifestyle and Biological Factors**:
Investigating how age, cholesterol levels, and exercise-induced angina contribute to heart disease.
Assessing gender-specific influences on heart disease risk.
 - **Understanding Chest Pain Types**:
 Analyzing the relationship between chest pain categories and heart disease risk.
Evaluating if specific chest pain types correlate strongly with other conditions, like higher cholesterol or blood pressure.
 - **Risk Stratification**:
Identifying high-risk groups using variable combinations (age, cholesterol, blood pressure).
Defining thresholds for risk indicators such as "old peak" or maximum heart rate ("thalachh").
 - **Analyzing Feature Interactions**:
Examining how the combination of features like cholesterol and thalassemia jointly affects heart disease risk.
## 4. KPI (Key Performance Indicators)
The study focuses on key performance metrics for assessing variable influence:
 - **Significance Values**: Chest pain (0.001), thalachh (0.010), oldpeak (0.022), caa (0.001), and thall (0.009).
 - **Adjusted R²**: 41.7% of the variance in the outcome is explained by independent factors.
 - **Beta Values**: Ranked in terms of impact on predicting heart disease:
                                                                       cp (0.222), caa (-0.197), thalachh (0.187), oldpeak (-0.158), thall (-0.146).
## 5. Analysis in a Short way:
![Image](https://github.com/user-attachments/assets/f9ab243d-042a-4289-b9f9-297920b584fe)
![Image](https://github.com/user-attachments/assets/ce2f5898-5cb9-466a-9973-cab588375cd0)
![Image](https://github.com/user-attachments/assets/92966eed-a13b-4c9c-81d3-c29371ab8504)
![Image](https://github.com/user-attachments/assets/c8fd9ca5-70ec-4f5a-bfb6-1ff1156a4635)
![Image](https://github.com/user-attachments/assets/c8890056-fad8-4998-821c-c6b5b03b48e1)
![Image](https://github.com/user-attachments/assets/bbbef1f2-7080-47a3-b8d9-882684ebb4b3)
![Image](https://github.com/user-attachments/assets/040c9667-68a9-472e-aee8-8dbb63e81111)
![Image](https://github.com/user-attachments/assets/04f77cea-d091-4208-8702-777bacc8e978)
![Image](https://github.com/user-attachments/assets/fda053cc-40e4-4761-b185-5b7273d8d6b6)
![Image](https://github.com/user-attachments/assets/abf8963e-2e0d-4e5f-a949-7d922cc7c389)
![Image](https://github.com/user-attachments/assets/7e967dd7-35c8-4414-a9d9-04d40cf9caf0)
![Image](https://github.com/user-attachments/assets/212e7988-0b00-48d6-bbe4-f644959c7ece)

## 6.	Interpretations of results: 
 - A.	To check whether the model is significant or not, we focus on the ANOVA table. In the table we check the significance value, and for this model
          Let,         H0 = Model is Insignificant.
                  and H1 = Model is Significant.
Now,                sig = 0.001 < p = 0.05 ………. Insignificant.
The null hypothesis is rejected, the model is significant.

 - B.	          Adjusted R2 = 0.417 = 41.7%
        That means 41.7% of the variance in the DV or Outcome Variable is explained by the IVs or predictor variable.

 - C.	Now, we’ll check which are the variables significant, for the hierarchy of the variables.
                  
            
These variables are significant. Now we’ll order them for check which variable is the most impactful.
So, 
For Hierarchy: we check the Beta Value of these variables.
                           The bigger the Beta, the Higher the Impact.
                           Always check magnitude value.
                      
Variables	Beta value	Order
cp	0.222	I
thalachh	0.187	III
oldpeak	-0.158	IV
caa	-0.197	II
thall	-0.146	V
     The biggest beta value is of “cp” i.e. 0.222, followed by caa, thalachh, oldpeak, and thall. Hence, cp is the most impactful variable.
This means that, if a person feels chest pain then it is a maximum possibility that the person is a heart patient or higher chance of getting a heart attack.

7.	Conclusions and Recommendations:
From our analysis, we can conclude that certain factors i.e. “cp” play a critical role in determining the heart disease patient, while others are less impactful. Among these factors, CP stands out as the most significant. 
To reduce heart disease and chest pain, patients should start morning and evening exercise.
And start eating a healthy diet, less workload, etc.

8.	Limitations:
•	The dataset should be large.
•	The categorical variables, such as sex, were treated as fixed categories without exploring potential interactions or more granular subcategories, which might have revealed subtle effects.
•	The analysis relies on a linear regression model, assuming linear relationships between predictors and the target variable. However, real-world relationships might be non-linear, leading to potential inaccuracies.
•	Interaction effects between variables, such as how Chest pain and Cholesterol level might jointly impact charges, were not explored. This could provide deeper insights.
















