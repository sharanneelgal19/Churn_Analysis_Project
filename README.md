 📊 Customer Churn Analysis

Overview

This project analyzes customer churn to understand customer behavior and identify customer groups associated with higher churn.

The project follows a complete data analytics workflow using Python for data cleaning and EDA and Power BI for interactive visualization. The findings are documented through a report and presentation.

Dataset

The dataset contains customer information related to:

* Customer demographics
* Services and subscriptions
* Contract type
* Payment method
* Monthly charges
* Total charges
* Customer tenure
* Churn status

The Churn variable is treated as the target variable, where 1 represents churn and 0 represents no churn. 

 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Power BI
* Microsoft PowerPoint

 🔄 Project Steps

 1. Data Loading

Loaded the customer churn dataset into Python using Pandas and performed an initial inspection of the dataset.

 2. Data Exploration

Explored the dataset using:

* head()
* shape
* value_counts()
* Missing-value checks
* Distribution analysis

 3. Data Cleaning

Cleaned the dataset by:

* Checking missing values
* Converting `TotalCharges` into numeric format
* Handling resulting missing values
* Preparing the dataset for analysis 

 4. Data Transformation

Converted categorical variables into dummy variables and transformed the `Churn` column into a binary format for numerical analysis. 

 5. Exploratory Data Analysis

Performed univariate and bivariate analysis using:

* Count plots
* Distribution plots
* KDE plots
* Correlation analysis
* Heatmaps

The analysis focused on variables such as tenure, monthly charges, internet service, online security, and technical support. 

 6. Power BI Dashboard

Created an interactive Power BI dashboard to visualize customer churn patterns and explore relationships between customer characteristics and churn.

 7. Report & Presentation

Created a project report and PowerPoint presentation covering the project objective, methodology, analysis, findings, and conclusions.

📊 Dashboard

The Power BI dashboard provides an interactive way to explore:

* Customer churn
* Customer characteristics
* Contract types
* Monthly charges
* Tenure
* Services
* Churn patterns

 💡 Results

The analysis identified several patterns associated with churn in this dataset:

* Month-to-month customers showed higher churn.
* Customers with higher monthly charges showed higher churn.
* First-year customers showed higher churn.
* Fiber optic customers showed higher churn.
* Customers without Online Security or Tech Support showed higher churn.
* Longer-tenure and long-term contract customers showed lower churn. 

These findings can help support further investigation and customer retention analysis.

📁 Project Structure

text
Customer-Churn-Analysis/
│
├── Dataset/
│   └── Customer-Churn.csv
│
├── Python/
│   └── Customer Churn Analysis (EDA).ipynb
│
├── PowerBI/
│   └── Customer Churn Analysis.pbix
│
├── Report/
│   └── Customer Churn Analysis Interview Explanation.pdf
│
├── Presentation/
│   └── Customer Churn Analysis.pptx
│
└── README.md

 How to Run

 Python

1. Clone or download this repository.
2. Install the required libraries:

bash
pip install pandas numpy matplotlib seaborn jupyter


3. Open the Jupyter Notebook.
4. Place the dataset in the appropriate folder.
5. Update the dataset path if required.
6. Run the notebook cells sequentially.

Power BI

1. Open Power BI Desktop.
2. Open the `.pbix` file.
3. Refresh the data if required.
4. Use the dashboard filters and visuals to explore the results.

 📌 Key Skills Demonstrated

Data Cleaning | Exploratory Data Analysis | Python | Pandas | NumPy | Data Visualization | Power BI | Customer Churn Analysis | Business Insights
