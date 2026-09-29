# Student Performance Analysis

## 1. Project Title

**Student Performance Analysis using Python**

## 2. Description

This project analyzes student performance data using Python.
The dataset contains students' marks in Mathematics, Reading, and Writing.

The project performs basic data analysis and calculates:

* Total Score
* Percentage
* Statistical details
* Missing values
* Math score outliers

## 3. Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## 4. Dataset

The project uses the **StudentsPerformance.csv** dataset.

The dataset is loaded using Pandas `read_csv()`.

## 5. Main Operations

### Data Loading

The CSV file is loaded into a Pandas DataFrame.

### Data Inspection

The project displays:

* First few records
* Last few records
* Dataset information
* Statistical summary
* Number of rows and columns

### Missing Value Checking

The project checks whether the dataset contains missing values.

### Score Analysis

The following scores are analyzed:

* Math Score
* Reading Score
* Writing Score

### Total Score

The total score is calculated as:

**Total Score = Math Score + Reading Score + Writing Score**

### Percentage

The percentage is calculated using:

**Percentage = Total Score × 100 / 300**

### Outlier Detection

The project uses the **IQR (Interquartile Range)** method to identify outliers in Mathematics scores.

## 6. Output

The program produces:

* Dataset preview
* Statistical summary
* Dataset information
* Missing-value count
* Total scores
* Percentages
* Number of math-score outliers

## 7. Conclusion

This project provides a simple analysis of student performance using Python and Pandas. It helps understand students' scores, calculate their overall performance, and identify unusual Mathematics scores.
