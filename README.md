# Findings

## Business Value Statement
This analysis is aimed to identify key factors influencing client subscription to term deposits, a priority for enhancing targeted marketing strategies. By comparing various models, including Logistic Regression, Decision Trees, and Support Vector Machines (SVM), we found that the K-Nearest Neighbors (KNN) model, with appropriate tuning, yielded the most balanced results for this dataset. KNN demonstrated superior sensitivity in identifying positive cases, meaning it can better detect clients who are likely to subscribe, which is crucial for improving marketing efficiency.

Key Findings
Using Permutation Feature Importance with KNN, the following factors emerged as the most influential for predicting the factors most important for user engagement (subscription to term deposit):

- Age: Clients' age showed the strongest correlation with subscription likelihood, indicating specific age groups are more inclined toward term deposits.
- Month: The month of the last contact also strongly influences subscription rates, suggesting seasonality impacts client interest.
- Contact Method: Clients contacted via telephone showed different behaviors than those contacted by other means, underscoring the importance of tailored communication channels.
- Day of the Week: The day of the week when contact was made has a notable influence, possibly reflecting variations in client availability and responsiveness.

## Strategic Insights
These insights provide actionable guidance for targeting potential clients:

- Target Age-Specific Marketing: Develop personalized strategies for age groups that are more likely to subscribe, optimizing resources for higher conversion.
- Seasonal Campaign Planning: Align marketing efforts with peak subscription months to capitalize on natural interest fluctuations.
- Optimized Communication Channels: Leverage the effectiveness of telephone communication, focusing resources on channels that yield higher engagement and conversion.
- Day-Specific Outreach: Schedule client contact strategically based on days that correlate with higher responsiveness, enhancing the efficiency of outreach efforts.

In summary, the KNN model's effectiveness, combined with the identification of these influential features, provides a robust foundation for a data-driven marketing strategy. By focusing on these key factors, the bank can improve targeting precision, maximize conversion rates, and increase term deposit subscriptions, thus optimizing marketing ROI.