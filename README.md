# EDA-For-Healthcare – Medical Appointment Analysis
Exploratory Data Analysis on Healthcare data using Python to find patterns, trends and insights.
## Project Overview
This project focuses on Exploratory Data Analysis (EDA) of medical appointment data to understand patient attendance patterns and identify the factors that influence whether patients attend or miss their scheduled medical appointments.
The analysis helps explore patient details, appointment schedules, health conditions, and SMS reminders to understand appointment attendance behaviour.

## Project Objectives
- Analyze patient appointment data.
- Understand patient attendance and no-show patterns.
- Explore the relationship between age, gender, and appointment attendance.
- Analyze the impact of health conditions on patient attendance.
- Study the relationship between SMS reminders and appointment attendance.
- Identify useful insights through data visualization.

## Dataset Description
The dataset contains 110,527 medical appointment records with 14 columns.
Important features include:
- Gender
- ScheduledDay
- AppointmentDay
- Age
- Neighbourhood
- Scholarship
- Hypertension
- Diabetes
- Alcoholism
- Handicap
- SMS_received
- No-show

The target variable is **No-show**, which indicates whether a patient attended or missed the appointment.
## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning and Preparation
- Loaded the dataset using Pandas.
- Checked dataset shape, information, and statistical summary.
- Converted appointment date columns into a standard date format.
- Extracted weekdays from scheduled and appointment dates.
- Renamed columns for better readability.
- Removed unnecessary patient ID, appointment ID, and neighbourhood columns from the analysis dataset.
- Checked for missing values and found no missing records.
- Created age groups for further analysis.
- Converted categorical variables into dummy variables.

## Exploratory Data Analysis
Performed different types of analysis to understand patient appointment behaviour:

- Univariate Analysis
- Bivariate Analysis
- Gender-wise Appointment Analysis
- Age Group Analysis
- Health Condition Analysis
- SMS Reminder Analysis
- Weekday-wise Appointment Analysis
- Correlation Analysis

## Data Visualization
Used Matplotlib and Seaborn to create:
- Bar Charts
- Count Plots
- Correlation Bar Charts
- Correlation Heatmaps

## Key Findings
1. Female patients booked more appointments than male patients.
2. Most age groups showed a higher appointment attendance rate.
3. Patients without scholarships showed a higher attendance rate compared to patients with scholarships.
4. Patients with hypertension showed a higher attendance rate than patients without hypertension.
5. Patients with diabetes showed a slightly higher attendance rate than patients without diabetes.
6. Patients who did not receive SMS reminders showed a higher attendance rate than those who received SMS reminders.
7. Sunday had no appointments, while Saturday had fewer appointments compared to other weekdays.

## Project Structure
EDA-for-Healthcare/
- Medical_Appointments_Data_EDA.ipynb
- Data.csv
- README.md

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries.

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open Jupyter Notebook.

```bash
jupyter notebook
```

4. Open `Medical_Appointments_Data_EDA.ipynb`.
5. Make sure `Data.csv` is in the same folder as the notebook.
6. Run all the cells to view the analysis and visualizations.

## Conclusion
This project helped me understand patient appointment attendance patterns through Exploratory Data Analysis. By analyzing patient information, health conditions, appointment schedules, and SMS reminders, I identified useful patterns and insights related to medical appointment attendance.

The project improved my practical knowledge of Python, data cleaning, data analysis, and data visualization.
