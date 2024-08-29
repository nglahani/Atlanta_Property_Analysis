# Atlanta Property Analysis

This project aimed to develop an advanced real estate valuation tool tailored for assessing home values and unique features in Atlanta, GA. By leveraging AI and Machine Learning, we sought to accurately cluster homes based on similar characteristics (e.g., home type, number of floors, proximity to city center) to enhance valuation precision through segmentation.

Our approach employed three distinct clustering algorithms—**K-Means**, **Spectral Clustering**, and **Gaussian Mixture Models**—to segment homes effectively. The Gaussian Mixture Model proved to be the most effective, identifying five distinct clusters of homes with unique traits. Additionally, **Principal Component Analysis (PCA)** was used for dimensionality reduction and visualization, aiding in the identification of significant patterns within the data.

Feature selection was performed using **LASSO regression** with cross-validation, which allowed us to isolate the most critical features influencing home values. The identified key features included the number of bedrooms, square footage, year built, number of bathrooms, latitude, number of floors, the presence of a fireplace, type of heating system, exterior material, and tax assessed values from recent years.

For a comprehensive overview of our methodology and findings, please refer to the full report available in **\ISyE6740_Final_Project.pdf** within this repository.

**Collaborators:** Nikolos Lahanis, Brendan Danyliuk, Luolin Shao
