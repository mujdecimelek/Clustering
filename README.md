# Customer Segmentation Using K-means Clustering

This project focuses on segmenting mall customers based on their annual income and spending habits using **K-means clustering**. The goal of this analysis is to identify key customer groups that can be targeted with tailored marketing strategies, thereby improving customer engagement and increasing sales.

## Dataset
The dataset used in this project is the **Mall Customer Segmentation Data**, which contains 5 key features:

- **CustomerID**: Unique identifier for each customer.
- **Gender**: Male or Female.
- **Age**: Age of the customer.
- **Annual Income (k$)**: Customer's annual income in thousands of dollars.
- **Spending Score (1-100)**: A score assigned by the mall based on customer spending habits.

## Project Structure

- **data/**: The folder containing the dataset.
- **notebooks/**: Jupyter notebooks with the clustering analysis and visualizations.
- **src/**: Python scripts for preprocessing, clustering, and visualization.

## Methods

1. **Data Preprocessing**: Cleaned and transformed the data, including:
   - Handled missing values (if any).
   - Converted categorical variables (such as Gender) into numerical values using Label Encoding.
   - Scaled numerical features to standardize the data.

2. **Clustering (K-means)**: 
   - Used the **K-means** algorithm to group customers into 5 distinct clusters based on their income and spending score.
   - Used the **elbow method** to determine the optimal number of clusters.

3. **Visualization**:
   - Created scatter plots to visualize the cluster distribution based on income and spending score.
   - Analyzed gender distribution within each cluster.

## Results and Insights

- Customers were divided into 5 distinct clusters, each with different income levels, spending behaviors, and age ranges.
- Based on the clustering results, specific marketing strategies are recommended for each customer segment.

### Example Clusters:
- **Cluster 2**: High-income, high-spending customers – these are the most valuable customers for the mall. Offering personalized services and exclusive deals is suggested.
- **Cluster 0**: Older customers with moderate spending – loyalty programs can be introduced to increase their engagement.

## Installation and Usage

To run the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/customer-segmentation.git
    ```

2. Navigate to the project directory:
    ```bash
    cd customer-segmentation
    ```

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter notebook to explore the analysis:
    ```bash
    jupyter notebook
    ```

## Technologies Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

## Conclusion

This project provides valuable insights into customer segmentation using K-means clustering. By identifying different customer groups based on spending habits and income levels, mall owners can implement personalized marketing strategies to increase sales and improve customer loyalty.
