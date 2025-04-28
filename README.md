# CM300_Phishing-URL-Detection
CM300 MSci Individual Project - Phishing URL Detection Implementation

# Think Before You Click: A Machine Learning Approach to Phishing URL Detection

In today’s digital climate, where an increasing amount of people are using the Internet as a platform to make online transactions, network, etc., cybersecurity has risen to the forefront as a critical issue for individuals, businesses, and governments alike. Among the vast variety of cyber threats, phishing remains one of the most prevalent and damaging attack vectors, as agreed by the Information Commissioner’s Office, and while anyone can be the victim of phishing, attackers are looking for high value returns, and therefore, large corporations are often the most targete. They account for 75% of all attacks, in 2022, which led to $2.7 billion in losses as shown in the FBI’s Internet Crime Report.

The detection of phishing URLs has become an important area of research within the cybersecurity community, as “traditional methods for detecting phishing websites, such as blacklist-based approaches, heuristic analysis, and rule-based systems, have become increasingly ineffective in combating these evolving threats”, (Chy & Hasan, 2024). Machine learning (ML) surfaced as a promising solution within cybersecurity, offering the capability to detect phishing attempts with increased accuracy and adaptability. These technologies enable the analysis of vast datasets to identify patterns and anomalies in URLs.

The research questions that aim to be answered within this body of work are:

1. How will a hybrid machine learning model perform in terms of real-time efficiency when compared to individually trained models?
2. Which Machine Learning models will have the highest accuracy in predicting the authenticity of a Phishing URL?

To do so, this project investigates the development of a phishing URL detection system using machine learning techniques. The system focuses solely on URL-based features, allowing for fast and accurate classification without relying on webpage content or external service queries.

Three baseline models, which included Decision Tree, Random Forest, and Support Vector Machine, were implemented, optimised, and evaluated. A hybrid model was also developed by stacking the optimised Random Forest and SVM models with XGBoost acting as the meta-classifier. The models were assessed on both predictive accuracy and real-time inference efficiency to reflect the demands of corporate cybersecurity environments.

## Key Features
- Preprocessing of publicly available phishing URL dataset

- Implementation and evaluation of individual baseline models

- Hyperparameter tuning using GridSearchCV

- Hybrid model construction using stacked generalisation

- Cross-validation using Stratified K-Fold

- Real-time inference time measurement for practical deployment analysis

- Visualisation of model performance and efficiency


## Acknowledgements
Special thanks to Dr. Mark Zarb, and The Zarbers, for their advice and support throughout the development of this project. 
