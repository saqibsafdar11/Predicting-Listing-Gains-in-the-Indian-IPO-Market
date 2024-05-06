## Predicting Listing Gains in the Indian IPO Market

# Overview
This project develops a TensorFlow-based deep learning model to predict listing gains for IPOs in the Indian market. Listing gains refer to the percentage increase in the share price from its IPO issue price on the listing day. This model aims to assist an investment firm in making informed decisions about investing in IPOs.

# Data
The dataset comprises historical data of various IPOs listed in the Indian market, sourced from moneycontrol. It includes details like the IPO name, issue size, subscription rates by different investor categories (QIB, HNI, RII), issue price, and the percentage listing gains.

# Data Dictionary
- Date: IPO listing date
- IPOName: Name of the IPO
- Issue_Size: Size of the IPO issue in INR Crores
- Subscription_QIB: Subscription rate by Qualified Institutional Buyers
- Subscription_HNI: Subscription rate by High Networth Individuals
- Subscription_RII: Subscription rate by Retail Individual Investors
- Subscription_Total: Total subscription rate
- Issue_Price: Issue price of the IPO in INR
- Listing_Gains_Percent: Percentage gain in the listing price over the issue price

# Libraries Used
- Numpy
- Pandas
- Seaborn
- Matplotlib
- TensorFlow

# Model Development
The project involves the use of TensorFlow and Keras for building a classification model that predicts whether an IPO will experience listing gains based on its pre-listing data. The following steps were taken:

- Loading and Exploring the Data
- Data Visualization
- Outlier Treatment
- Setting the Target and Predictor Variables
- Define the Deep Learning Classification Model
- Define the Deep Learning Classification Model
- Compile and Train the model
- Model Evaluation

# Conclusion
The model provides an analytical basis for predicting the financial outcome of investing in an IPO, potentially guiding investment strategies with data-driven insights. The accuracy was approximately 75% on the training data and 69% on the test data.
 
