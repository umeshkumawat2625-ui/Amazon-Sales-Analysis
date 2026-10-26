# E-Commerce Sales Analysis

## Project Overview

This project analyzes retail/e-commerce sales data using **Python, Pandas, and Plotly**. The analysis explores sales and profit over time, compares product categories and sub-categories, and examines performance across customer segments.

The goal is to turn transaction-level data into useful business insights that can help identify sales trends and understand profitability.

## Business Questions

- Which month has the highest and lowest sales?
- Which product categories generate the highest and lowest sales?
- How do sales vary across product sub-categories?
- Which month has the highest profit?
- How do profit results differ by category and sub-category?
- How do sales and profit compare across customer segments?
- What is the relationship between sales and profit?

## Tools & Libraries

- **Python** — analysis and scripting
- **Pandas** — loading, cleaning, transforming, and summarizing tabular data
- **Plotly Express** — interactive charts
- **Plotly Graph Objects** — customizable visualizations
- **Jupyter Notebook** — interactive analysis environment

## Dataset

The notebook loads a file named `Sample - Superstore.csv`. The preview in the notebook shows fields including:

| Field | Description |
|---|---|
| `Order Date` | Date the order was placed |
| `Ship Date` | Date the order was shipped |
| `Ship Mode` | Shipping method |
| `Customer ID`, `Customer Name` | Customer identifiers and names |
| `Segment` | Customer segment |
| `Country`, `City`, `State`, `Region` | Geographic information |
| `Category`, `Sub-Category` | Product classification |
| `Product Name`, `Product ID` | Product details |
| `Sales` | Sales amount |
| `Quantity` | Quantity ordered |
| `Discount` | Discount applied |
| `Profit` | Profit or loss for the order line |

The notebook preview reports **9,994 records and 21 columns**. The analysis also derives date-related fields such as order month, year, and day for time-based comparisons.

## Analysis Workflow

1. **Load the data** from the CSV file with Pandas.
2. **Review descriptive statistics** to understand numeric fields and their distributions.
3. **Prepare date fields** for month-, year-, and day-level analysis.
4. **Aggregate sales and profit** by time period, category, sub-category, and customer segment.
5. **Visualize patterns** with Plotly charts.
6. **Compare performance** to identify high- and low-performing periods and product groups.

## Analysis Areas

### 1. Monthly Sales
Compare sales across months and identify the highest- and lowest-sales periods.

### 2. Category and Sub-Category Performance
Evaluate sales and profit across product categories and their sub-categories.

### 3. Monthly Profit
Review profit by month to identify periods with stronger profitability.

### 4. Customer Segment Analysis
Compare sales and profit across customer segments.

### 5. Sales-to-Profit Relationship
Explore sales alongside profit to better understand profitability. Note that a sales-to-profit ratio should be defined consistently and interpreted carefully when profit is zero or negative.

## Repository Structure

```text
E-Commerce-Sales-Analysis/
├── README.md
├── e commerce sales.ipynb
└── Sample - Superstore.csv
```

The CSV is referenced by the notebook. Include it in the repository (if licensing permits), or update the notebook's file path to match wherever you store the dataset.

## How to Run

1. Clone or download this repository.
2. Install Python if it is not already installed.
3. Install the required libraries:

   ```bash
   pip install pandas plotly jupyter
   ```

4. Make sure `Sample - Superstore.csv` is available in the path used by the notebook.
5. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `e commerce sales.ipynb` and run the cells.

## Skills Demonstrated

- Exploratory data analysis (EDA)
- Data loading and transformation with Pandas
- Date-based analysis
- Grouped sales and profit analysis
- Interactive data visualization with Plotly
- Translating business questions into analytical steps

## Possible Enhancements

- Add a concise findings section with verified results from the notebook.
- Include screenshots of selected charts.
- Add data-quality checks for missing values and duplicate records.
- Document the exact formula used for sales-to-profit ratio.
- Make chart labels, titles, currency formatting, and axis names consistent.

## Author

**Umesh Kumawat**  
Data Analytics Portfolio Project

---

*This README describes the analysis questions and workflow documented in the project files. Add specific numerical findings only after verifying them from the notebook outputs.*
