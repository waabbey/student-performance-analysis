# Student Math Performance Analysis

A beginner exploratory data analysis and linear regression project using the UCI Student Performance dataset (`student-mat.csv`) to see how study habits, past grades, and lifestyle factors relate to final math grades (`G3`).

## Key Results
- **With prior grades (`G1`, `G2`) + habits/background:** `MAE = 1.37`, `R² = 0.77`
- **Habits & background only (no `G1`/`G2`):** `MAE = 3.67`, `R² = -0.01`
- **Expanded habits & lifestyle (no `G1`/`G2`):** `MAE = 3.59`, `R² = 0.04`

## What I Learned
- Earlier exam scores (`G2` and `G1`) carry the strongest predictive signal for final grades, while `failures` correlates negatively.
- Habit and lifestyle variables alone explain very little variance in a simple linear model without academic performance history.

## How to Run
Open `student_performance_project.ipynb` in **Google Colab**, upload `student-mat.csv` to the files sidebar, and click **Runtime > Run all**.
