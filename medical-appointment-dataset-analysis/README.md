Medical Appointment No-Show Analysis
Overview
This project analyzes a medical appointment dataset to understand factors affecting patient no-shows. The dataset includes patient demographics, appointment details, and medical conditions.

Dataset
File: noshowappointments-kagglev2-may-2016.csv

Contains appointment records with details such as age, gender, medical history, and whether the patient showed up.

Project Workflow
1. Data Cleaning
Dropped unnecessary columns (e.g., PatientId, AppointmentId).

Converted date columns to appropriate formats.

Added a new column for days until the appointment.

Converted categorical variables to boolean types.

Cleaned inconsistencies in the Handcap and Age columns.

2. Exploratory Data Analysis (EDA)
Analyzed appointment attendance by gender.

Identified factors contributing to no-shows using visualization techniques.

Installation & Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/medical-appointment-analysis.git
cd medical-appointment-analysis
Install dependencies:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn jupyter
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook medical-appointment-dataset-analysis.ipynb
Dependencies
Python

Pandas

NumPy

Matplotlib

Seaborn

Results & Insights
Women had a higher appointment attendance rate than men.

Certain medical conditions and reminders (SMS) influenced attendance.
