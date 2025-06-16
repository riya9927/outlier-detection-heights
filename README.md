# Outlier Detection in Heights Dataset

This project demonstrates how to detect and remove outliers from a dataset using statistical methods such as Standard Deviation (Z-Score) and Interquartile Range (IQR). The dataset used contains height data of 10,000 individuals.

---

## Objective

- Identify outliers using the 3-sigma rule (Z-Score).
- Detect outliers using the IQR method.
- Visualize and analyze the cleaned dataset.

---

## Dataset

**Filename:** `heights.csv`  
**Columns:**
- `gender`
- `height`

---

## Methods Used

### 1. Z-Score Method

A point is considered an outlier if:
- `z-score > 3` or `z-score < -3`

### 2. IQR Method

A point is considered an outlier if:
- height > Q3 + 1.5*IQR or height < Q1 - 1.5*IQR

---

## Visualization

- Histogram to show the distribution of height values.
- Boxplot to easily observe the presence of outliers.
- Z-Score vs Height scatter plot to see deviation.

---

## Conclusion

Outlier detection is crucial for ensuring data quality and robust analysis. This project shows how both the Z-Score and IQR methods effectively detect extreme values for removal or investigation.

