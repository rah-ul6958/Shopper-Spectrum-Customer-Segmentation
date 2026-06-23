# 🛒 Shopper Spectrum: Customer Segmentation & Product Recommendation System

An end-to-end Machine Learning project that analyzes e-commerce transaction data to identify customer segments and generate personalized product recommendations.

## 📌 Project Overview

E-commerce platforms generate large volumes of transactional data every day. Understanding customer behavior from this data can help businesses improve customer retention, optimize marketing strategies, and increase sales.

This project focuses on:

- Customer Segmentation using K-Means Clustering
- Product Recommendation using Item-Based Collaborative Filtering
- Exploratory Data Analysis (EDA)
- Customer Behavior Analysis using RFM Metrics

---

## 🎯 Objectives

- Analyze customer purchasing patterns
- Segment customers into meaningful groups
- Identify high-value and at-risk customers
- Build a recommendation engine for personalized product suggestions
- Generate business insights from transaction data

---

## 📊 Dataset

**Dataset:** Online Retail Dataset

The dataset contains transactional records from an online retail store, including:

- Invoice Number
- Product Description
- Quantity
- Unit Price
- Customer ID
- Country
- Invoice Date

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- OpenPyXL

---

## 📈 Exploratory Data Analysis

The project performs extensive EDA including:

- Missing Value Analysis
- Duplicate Record Removal
- Revenue Analysis
- Country-wise Sales Analysis
- Product Performance Analysis
- Monthly Revenue Trends
- Customer Purchase Behavior Analysis

### Key Visualizations

- Transaction Distribution
- Top Selling Products
- Monthly Revenue Trends
- Revenue by Country
- Hourly Transaction Analysis
- RFM Feature Analysis
- Correlation Heatmaps
- Pair Plots

---

## 👥 Customer Segmentation

### RFM Analysis

Customers are segmented using:

- **Recency (R)** → How recently a customer purchased
- **Frequency (F)** → How often a customer purchases
- **Monetary (M)** → How much a customer spends

### Clustering Algorithm

**K-Means Clustering**

The optimal number of clusters was selected using:

- Elbow Method
- Silhouette Score Analysis

### Customer Segments

| Segment | Description |
|----------|-------------|
| High-Value | Frequent buyers with high spending |
| Regular | Consistent customers with moderate spending |
| Occasional | Infrequent customers with low spending |
| At-Risk | Customers who have not purchased recently |

---

## 🎁 Product Recommendation System

### Approach

Item-Based Collaborative Filtering

The recommendation system:

1. Creates a Customer-Product interaction matrix
2. Calculates Cosine Similarity between products
3. Recommends similar products based on purchase patterns

### Benefits

- Personalized recommendations
- Improved customer experience
- Increased cross-selling opportunities
- Better customer engagement

---

## 📊 Business Insights

### Revenue Trends

- Q4 (October–November) shows peak revenue generation.
- Seasonal demand patterns can guide inventory planning.

### Geographic Insights

- United Kingdom contributes the highest sales volume.
- Germany and Netherlands show strong international purchasing behavior.

### Customer Insights

- High-Value customers contribute a major portion of revenue.
- At-Risk customers require targeted retention campaigns.
- Personalized promotions can help convert Regular customers into High-Value customers.

### Marketing Insights

- Peak transaction hours occur between 10 AM and 3 PM.
- Marketing campaigns can be optimized during these hours.

---

## 📂 Project Structure

```text
Shopper-Spectrum-Customer-Segmentation/
│
├── Shopper_Spectrum_Customer_Segmentation.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Shopper-Spectrum-Customer-Segmentation.git
cd Shopper-Spectrum-Customer-Segmentation
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Notebook

```bash
jupyter notebook
```

Open:

```text
Shopper_Spectrum_Customer_Segmentation.ipynb
```

---

## 🔮 Future Enhancements

- DBSCAN Clustering
- Hierarchical Clustering
- Matrix Factorization (SVD)
- Customer Lifetime Value Prediction
- Real-Time Recommendation Engine
- Streamlit Deployment

---

## 📜 License

This project is created for educational and learning purposes.

---

## 👨‍💻 Author

**Rahul Yadav**

B.Tech CSE Student  
Machine Learning & Data Science Enthusiast

---

⭐ If you found this project useful, consider giving it a star on GitHub.
