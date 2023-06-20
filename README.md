# Lead Score Prediction Assignment

## Problem Statement:
X Education sells online courses to industry professionals. The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals.

Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

## Business Goal:
X Education needs help in selecting the most promising leads, i.e. the leads that are most likely to convert into paying customers.

The company needs a model wherein a lead score is assigned to each of the leads such that the customers with higher lead scores have a higher conversion chance and the customers with lower lead scores have a lower conversion chance.

The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

### Code
Code File - Lead Score Assignment.ipynb

<b>Major Steps taken to solve this Problem Statement are:</b>
1. Reading & Understanding Data
2. Exploratory Data Analysis<br>
  2.1. Handling Missing Values<br>
  2.2. Categorical Features Analysis<br>
  2.3. Numerical Features Analysis & Outlier Detection<br>
3. Data Analysis<br>
  3.1. For Categorical Features<br>
  3.2. For Numerical Features<br>
4. Data Pre-Processing
5. Data Split
6. Handling Multicollinearity Within Independent Features via Correlation
7. Feature Scaling
8. Feature Selection & Model Building
9. Model Evaluation on the Train Data<br>
  9.1. Basic Metrics<br>
  9.2. Plotting the ROC Curve<br>
10. Optimal Probability Cut-Off<br>
  10.1. Accuracy, Sensitivity & Specificity Trade-Off Curve<br>
  10.2. Precision-Recall Trade-Off Curve<br>
11. Making Predictions on the Test Dataset
12. Model Evaluation on Test Data<br>
  12.1. Basic Metrics<br>
  12.2. Plotting the ROC Curve<br>
13. Generating Lead Scores for Test Data

### Conclusion:
- On Training Data, we have achieved a <b>78.39% Conversion Rate</b> using <b>0.37 as the Optimal Probability Cut-Off</b> & using the same Cut-Off on Test Data we have achieved a <b>79.64% Conversion Rate</b>. Therefore, we can conclude that for both Datasets we have approx <b>80% Lead Conversion Rates which was asked by X Educations CEO</b>.
- <b>Hence, this model seems to be good for Lead Scoring.</b>
