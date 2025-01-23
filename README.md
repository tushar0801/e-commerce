
# Retail Data Analysis Project

## Overview
This project involves a comprehensive analysis of retail data using advanced data science techniques. It covers three major tasks:

1. **Exploratory Data Analysis (EDA) and Business Insights**  
2. **Lookalike Model Development**  
3. **Customer Segmentation using Clustering**

The insights and models developed aim to assist the business in understanding customer behavior, identifying similar customers, and segmenting customers for targeted marketing strategies.

---

## Dataset Description
The project utilizes three datasets:

1. **Customers.csv**  
   - **CustomerID**: Unique identifier for each customer.  
   - **CustomerName**: Name of the customer.  
   - **Region**: Continent where the customer resides.  
   - **SignupDate**: Date when the customer signed up.

2. **Products.csv**  
   - **ProductID**: Unique identifier for each product.  
   - **ProductName**: Name of the product.  
   - **Category**: Product category.  
   - **Price**: Product price in USD.

3. **Transactions.csv**  
   - **TransactionID**: Unique identifier for each transaction.  
   - **CustomerID**: ID of the customer who made the transaction.  
   - **ProductID**: ID of the product sold.  
   - **TransactionDate**: Date of the transaction.  
   - **Quantity**: Quantity of the product purchased.  
   - **TotalValue**: Total value of the transaction.  
   - **Price**: Price of the product sold.

---

## Tasks and Deliverables

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- **Objective**: Perform EDA to derive actionable business insights.  
- **Key Highlights**:  
  - Customer distribution by region.  
  - Spending trends and customer segmentation.  
  - Product performance analysis.  
  - Seasonal and temporal sales trends.  

**Deliverables**:  
- A Jupyter Notebook/Python script with EDA code.  
- PDF report summarizing 5 key business insights.

**File Names**:  
- `FirstName_LastName_EDA.pdf`  
- `FirstName_LastName_EDA.ipynb`

---

### Task 2: Lookalike Model Development
- **Objective**: Develop a model that identifies similar customers based on profile and transaction data.  
- **Approach**:  
  - Compute similarity scores using profile and transactional data.  
  - Recommend the top 3 lookalike customers for the first 20 customers (CustomerID: C0001 to C0020).

**Deliverables**:  
- CSV file containing the lookalike recommendations with similarity scores.  
- Jupyter Notebook/Python script explaining the model development.

**File Names**:  
- `FirstName_LastName_Lookalike.csv`  
- `FirstName_LastName_Lookalike.ipynb`

---

### Task 3: Customer Segmentation / Clustering
- **Objective**: Segment customers into clusters for targeted marketing.  
- **Approach**:  
  - Use K-Means clustering with optimal clusters determined via the Elbow Method.  
  - Evaluate clustering performance using the Davies-Bouldin Index.  
  - Visualize clusters using PCA.

**Key Metrics**:  
- Number of Clusters: 3  
- Davies-Bouldin Index: 1.43  

**Deliverables**:  
- A report summarizing clustering results and metrics.  
- Jupyter Notebook/Python script containing clustering code.

**File Names**:  
- `FirstName_LastName_Clustering.pdf`  
- `FirstName_LastName_Clustering.ipynb`

---

## Repository Structure
The repository follows the structure below:
```
📂 Retail_Data_Analysis
├── 📄 FirstName_LastName_EDA.ipynb
├── 📄 FirstName_LastName_EDA.pdf
├── 📄 FirstName_LastName_Lookalike.ipynb
├── 📄 FirstName_LastName_Lookalike.csv
├── 📄 FirstName_LastName_Clustering.ipynb
├── 📄 FirstName_LastName_Clustering.pdf
├── 📂 Data
│   ├── Customers.csv
│   ├── Products.csv
│   ├── Transactions.csv
└── 📄 README.md
```

---

## Insights and Observations
### Key Business Insights from EDA
1. **Customer Distribution**: Customers are unevenly distributed across regions, with Regions X and Y contributing 60% of the customer base.  
2. **Spending Patterns**: High spenders (15% of customers) contribute significantly to revenue.  
3. **Product Performance**: Electronics dominate sales, while Categories Z and W underperform.  
4. **Churn Analysis**: 25% of customers are inactive for over 90 days, highlighting retention opportunities.  
5. **Temporal Trends**: Sales peak during evenings and weekends, with seasonal spikes in months A and B.

### Lookalike Model Observations
- **Similarity Scores**: The model effectively identifies similar customers based on profile and transactional attributes.
- **Recommendations**: Personalized marketing campaigns can be developed using the recommended lookalikes.

### Clustering Insights
- **Cluster Profiles**:  
  - Cluster 0: High spenders with frequent transactions.  
  - Cluster 1: Moderate spenders.  
  - Cluster 2: Low spenders with minimal diversity in purchases.  
- **DB Index**: The low Davies-Bouldin Index of 1.43 reflects well-separated and compact clusters.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your_username>/Retail_Data_Analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Retail_Data_Analysis
   ```

3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebooks in sequence:
   - `EDA.ipynb` for exploratory analysis and insights.  
   - `Lookalike.ipynb` for generating lookalike recommendations.  
   - `Clustering.ipynb` for customer segmentation.

---

## Tools and Technologies
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Visualization**: PCA, Cluster Visualizations, and Temporal Trends

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Author
**Tushar Buttan**  
Feel free to connect via [LinkedIn](https://linkedin.com/in/<your-profile>) or email at `<your-email>` for any queries or collaborations.
