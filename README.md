# Customer-Segmentation
**AlmaBetter Verified Project**

![pie-segment-760 (1)](https://user-images.githubusercontent.com/100474431/174673287-3929f307-5ad2-4bd6-89ce-cca9e09f7453.jpg)

# **Problem Statement:**
Online Retail Customer Segmentation Online-Retail-Customer-Segmentation In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## **The need of customer segmentation:**

The differences in customers' behaviour, demographics, geographies, etc. help in classifying them in groups. Learning about different groups in the customer can help with following:

Target Marketing, Client understanding, Optimal product placement, Searching for new customers Revenue growth.

## **Recency-Frequency-Monetary (RFM) model to determine customer value:**

The RFM model is quite useful model in retail customer segmentation where only the data of customer transaction is available. RFM stands for the three dimensions:

Recency – How recently did the customer purchase? Frequency – How often do they purchase? Monetary Value – How much do they spend? A combination of these three attributes can be defined to assign a quantitative value to customers. e.g. A customer who recently bought high value products and transacts regularly is a high value customer.

## 📖 **Segmentation with K-means clustering:**

Initially, the data is subject to important stages in an analytics pipeline: exploratory analysis, preprocessing, feature engineering and standardizaton. Then, the unsupervised classification technique, K-means clustering algorithm, is used to determine the ideal segments of customers. Silhouette analysis and related cluster visualizations are leveraged to deduce the optimum value of "K" (number of clusters) in the algorithm. The observations from the results are elaborately discussed before reaching the conclusion from the business perspective.

## 💾 **Project Files Description:**

This Project includes 1 colab notebook and 1 presentation Pdf.

### **Executable Files:**

[Online_Retail_Customer_Segmentation](https://github.com/roysoni24/Customer-Segmentation/blob/main/Copy_of_Online_Retail_Customer_Segmentation_Capstone_Project.ipynb) - Includes all Exploratory Data Analysis and all functions required for Clustering operations.

[customer segmentation ppt.pdf](https://github.com/roysoni24/Customer-Segmentation/blob/main/Copy_of_Online_Retail_Customer_Segmentation_Capstone_Project.ipynb) - Includes pdf of presentation of the project.

### **Output:**

[Google Colab](https://github.com/roysoni24/Customer-Segmentation/blob/main/Copy_of_Online_Retail_Customer_Segmentation_Capstone_Project.ipynb) - All the outputs are visible in the provided colab notebook.


## 📋 **Execution Instruction:**

The order of execution of the colab notebook is as follows:

**1) Online_Retail_Customer_Segmentation_Capstone_Project.ipynb**

First, click on the open in colab button present on the top center of the notebook.

In this .ipynb file, we have -

• EDA on online retail customer segmentation.

• RFM Analysis.

• Clustering Analysis.

**2) Kaggle Dataset**

Downlaod the dataset from kaggle through provided link.Then, connect to the runtime and execute the cell to mount the drive or upload the data file to the current runtime.

**3) Cell Path**

Finally, delete the path in the dataset loading cell and replace it with the path of your current data file. Run each cell to see the output below it.

## **Conclusions**

• K-Means Clustering with Silhouette gives the highest score of 0.39 for number of clusters 2.

• Sales has been increased from 2010 to 2011.

• The business can focus on these different clusters and provide to customers of each sector in a different way, which would not only benefit the customer but also the business at large.

## 📜 **Credits**

Soni Rani | Vivek Kumar | Suraj Singh

## 📚 **References**
1. RFM Analysis - https://clevertap.com/blog/rfm-analysis/
2. K-Means Clustering - https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html
3. Elbow Method - https://www.scikit-yb.org/en/latest/api/cluster/elbow.html

