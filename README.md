# Face Recognition Attendance Data – Cleaning & Visualization

## Internship Task
**Task:** Data Cleaning & Visualization  
**Domain:** Face Recognition Attendance System

## Objective
This project uses attendance records to demonstrate:
- Data cleaning
- Missing-value handling
- Duplicate removal
- Date/time standardization
- Attendance analysis
- Data visualization

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Files
- `attendance_raw.csv` – raw dataset containing deliberate data-quality issues
- `attendance_cleaned.csv` – cleaned dataset
- `student_attendance_summary.csv` – student-wise analysis
- `daily_attendance_summary.csv` – daily attendance analysis
- `department_summary.csv` – department comparison
- `data_cleaning_visualization.ipynb` – complete Python notebook
- `visualizations/` – generated charts

## Main Findings
- Total students analyzed: 20
- Clean attendance records: 399
- Present records: 329
- Late records: 40
- Absent records: 30
- Overall attendance rate: 92.48%

## How to Run
1. Install Python.
2. Install required libraries:
   `pip install pandas matplotlib jupyter`
3. Open the project folder in Jupyter Notebook.
4. Open `data_cleaning_visualization.ipynb`.
5. Run all cells.

## Submission Note
The dataset is a realistic sample dataset created for demonstrating the internship task. If your actual face-recognition project exports attendance data, replace `attendance_raw.csv` with the real CSV and rerun the notebook.
