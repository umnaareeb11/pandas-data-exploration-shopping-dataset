 Shopping Dataset — Data Exploration & Cleaning with Pandas

A beginner Python & Pandas project that performs end-to-end data exploration and cleaning on a real-world shopping dataset from Kaggle.

---

 About the Project

This project was completed as part of a **Python & Pandas beginner assignment**. The goal was to learn how to load, explore, clean, and export a real-world CSV dataset using industry-standard data science practices.

The dataset used is the **Shopping Dataset (Ecommerce Products & Sizes)** from Kaggle. Through this project, I learned how to handle missing values, remove duplicates, filter and sort data, and create derived columns — all essential skills in data analysis.

---

  Dataset

| Property | Details |
|---|---|
| Source | [Kaggle — Shopping Dataset by anvitkumar](https://www.kaggle.com/datasets/anvitkumar/shopping-dataset) |
| Format | CSV |
| Description | Ecommerce product data including products, sizes, prices, and quantities |

> **Note:** The dataset is not included in this repository. Please download it directly from Kaggle and place the CSV file in the project folder before running the notebook.

---

 Objectives

-  Load a CSV dataset into a Pandas DataFrame
- Explore the dataset (shape, columns, data types, statistics)
-  Identify and handle missing values
-  Perform basic operations (filter, select, sort)
-  Remove duplicate records
-  Create a derived column `total_amount = price × quantity`
-  Save the cleaned dataset as a new CSV file

---

 Project Structure

```
pandas-data-exploration-shopping-dataset/
│
├── shopping_data_exploration.ipynb    ← Main Jupyter Notebook (all steps)
├── cleaned_shopping_dataset.csv       ← Output: cleaned data (auto-generated)
├── shopping_dataset.csv               ← Original dataset (download from Kaggle)
└── README.md                          ← This file
```

---

 🛠️ Technologies Used

| Tool | Purpose |
|---|---|
| Python 3.x | Programming language |
| Pandas | Data loading, exploration, and cleaning |
| NumPy | Numerical operations |
| Jupyter Notebook | Interactive coding environment |

---

 ⚙️ How to Run

Step 1 — Clone this repository
```bash
git clone https://github.com/YOUR_USERNAME/pandas-data-exploration-shopping-dataset.git
cd pandas-data-exploration-shopping-dataset
```

Step 2 — Install required libraries
```bash
pip install pandas numpy jupyter
```

Step 3 — Download the dataset
1. Go to: https://www.kaggle.com/datasets/anvitkumar/shopping-dataset
2. Click **Download** (requires a free Kaggle account)
3. Extract the ZIP file
4. Place the `.csv` file inside the project folder

Step 4 — Launch Jupyter Notebook
```bash
jupyter notebook
```

Step 5 — Run the notebook
- Open `shopping_data_exploration.ipynb`
- Run all cells top to bottom using **Shift + Enter**

---

Steps Performed in the Notebook

| Step | Description |
|---|---|
| **Step 0** | Import libraries (pandas, numpy) |
| **Step 1** | Load CSV — auto-detects filename |
| **Step 2** | Explore data — head, tail, shape, columns, dtypes, describe, info |
| **Step 3** | Handle missing values — median fill for numbers, 'Unknown' for text |
| **Step 4** | Basic operations — select columns, filter rows, sort data |
| **Step 5** | Remove duplicate rows and reset index |
| **Step 6** | Create `total_amount` column using smart column detection |
| **Step 7** | Save cleaned dataset as `cleaned_shopping_dataset.csv` |
| **Step 8** | Final summary report with key insights |

---

Key Findings

>  *Fill this section after running the notebook with your actual results.*

- **Total rows in original dataset:** _(add after running)_
- **Total columns:** _(add after running)_
- **Missing values handled:** _(add after running)_
- **Duplicate rows removed:** _(add after running)_
- **New column created:** `total_amount = price × quantity`
- **Cleaned dataset saved as:** `cleaned_shopping_dataset.csv`

**Sample Insights:**
- _(e.g., Most products belong to the category '...')_
- _(e.g., Average price of products is ₹...)_
- _(e.g., The highest total_amount transaction was ₹...)_

---

##  What I Learned

- How to load and inspect a real-world CSV dataset using Pandas
- How to identify and handle missing values using `fillna()` and `dropna()`
- How to filter, sort, and select data from a DataFrame
- How to detect and remove duplicate rows
- How to create new derived columns from existing ones
- How to export a cleaned DataFrame back to a CSV file
- Writing clean, well-commented, beginner-friendly Python code

---

Challenges Faced

- Understanding the difference between `NaN` and empty strings
- Deciding whether to fill or drop missing values
- Finding the right column names for `price` and `quantity` automatically
- Learning how `reset_index()` works after dropping rows

---

 Future Improvements

- Add data visualization using Matplotlib or Seaborn
- Perform groupby analysis (e.g., sales by category)
- Build a simple dashboard using Plotly
- Connect to a SQL database for querying

---

  Author

**Umna Areeb**
- GitHub: [@umnaareeb11](https://github.com/umnaareeb11)
- LinkedIn: [Umna Areeb](https://www.linkedin.com/in/umna-areeb-949752348)

---

📄 License

This project is open source and available under the [MIT License](LICENSE).

---

  Acknowledgements

- Dataset by [anvitkumar](https://www.kaggle.com/anvitkumar) on Kaggle

---
