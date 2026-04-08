Fraud Detection System with Behavioral Analytics

This project presents an end-to-end fraud detection pipeline that combines machine learning and data visualization to identify and monitor fraudulent transactions.

Objective

To build a data-driven system capable of detecting fraud based on behavioural patterns while providing interpretable insights for decision making.

Approach Summary
Integrated transaction, device, and IP datasets
Engineered behavioural features such as transaction velocity and device activity
Addressed class imbalance using SMOTE
Trained and evaluated multiple models
Selected Random Forest as the best-performing model
Built an interactive dashboard using Tableau
Model Performance
Model	Recall	Precision	F1 Score
Random Forest	0.89	0.98	0.93
XGBoost	0.83	0.97	0.90
Logistic Regression	0.61	0.98	0.75
Key Insights
Fraud tends to occur in high-frequency transaction bursts
Device and IP reuse are strong indicators of suspicious activity
Temporal patterns significantly influence fraud detection
Behavioural features improve model performance more than static attributes
Dashboard

The dashboard provides:

Fraud trend analysis
Device and IP risk monitoring
Transaction behaviour insights
Model performance tracking
Estimated financial impact
Challenges
Incomplete fraud labels required alternative strategies
Class imbalance affected early model performance
Feature engineering required iterative refinement
Conclusion

This project demonstrates how behavioural analytics and machine learning can be combined to build an effective fraud detection system.
