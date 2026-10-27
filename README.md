# 🏠 King County House Price Data Analysis

## 📌 Project Overview
This project focuses on analyzing house price data using Python. It explores property prices, living area, lot size, construction year, renovation details, and other housing features.

The project uses data analysis techniques to understand the dataset, create new features, identify outliers, and visualize house price information.

## 🎯 Objectives
- Explore and understand the house price dataset.
- Check missing values and duplicate records.
- Convert sale dates into datetime format.
- Calculate property age and years since renovation.
- Calculate price per square foot for living area and lot size.
- Detect outliers using the Interquartile Range (IQR) method.
- Visualize outliers using box plots.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Dataset
**Dataset file:** `kc_house_data.csv`

The dataset contains housing information such as:
- `price` – House selling price
- `date` – Date of sale
- `sqft_living` – Living area in square feet
- `sqft_lot` – Lot size in square feet
- `yr_built` – Year the house was built
- `yr_renovated` – Year the house was renovated

## ⚙️ Project Workflow
1. Import the required Python libraries.
2. Load the dataset using Pandas.
3. Explore the first and last rows of the dataset.
4. Check column names, data types, shape, and statistical summaries.
5. Check missing values and duplicate records.
6. Convert the sale date into datetime format and extract the sale year.
7. Calculate property age and renovation-related features.
8. Calculate price per square foot for living area and lot size.
9. Detect outliers using the IQR method.
10. Display box plots to visualize outliers.

## 📊 Visualizations
The project includes box plots for:
- Price per square foot of living area.
- Price per square foot of lot size.

These visualizations help identify unusually high or low values in the data.

## 🚀 How to Run the Project
1. Download or clone this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Place `kc_house_data.csv` in the appropriate folder.
4. Open `kc_house.ipynb` using Jupyter Notebook or Google Colab.
5. Update the dataset file path if necessary.
6. Run all cells in order.

## ✅ Expected Outcome
- Better understanding of house price data.
- Additional property-related features for analysis.
- Identification of missing values, duplicates, and outliers.
- Box plot visualizations for price per square foot.

## 📝 Conclusion
This project demonstrates how Python libraries can be used for housing data analysis, feature engineering, outlier detection, and data visualization. It helps understand important property characteristics and their relationship to housing prices.

## 👩‍💻 Author
**Reenu**

## 📄 License
This project is intended for educational and learning purposes.
