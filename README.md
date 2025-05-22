
# Practical Machine Learning: Prediction Assignment Writeup

**Author:** Shifa Rizkillah Hidayat

## Overview

This project involves predicting how participants performed barbell lifts using accelerometer data from sensors worn on different body parts.

The model used is a Random Forest classifier trained with 5-fold cross-validation. Data cleaning steps included removing near-zero variance predictors and columns with high missing data.

Predictions for 20 test cases are generated and saved as individual text files inside the `predictions/` folder.

## Files in this repository

- `practical_ml_assignment.Rmd` — The R Markdown source file with full analysis and code.
- `predictions/problem_id_*.txt` — Text files containing predictions for each test case (generated after running the R Markdown).
- `README.md` — This file.

## How to Run

1. Open the `practical_ml_assignment.Rmd` in RStudio.
2. Knit the file to HTML.
3. Run the code chunks to generate predictions.
4. The prediction files will be saved in the `predictions` folder.

## Submission

- Submit the knitted HTML output.
- Submit the 20 prediction files in the appropriate format as specified by the Coursera assignment.

---

*Prepared by Shifa Rizkillah Hidayat*
