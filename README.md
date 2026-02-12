# Behavioral Health Unit Operational Insights

This project analyzes a fictional behavioral health unit's daily operations over a 90‑day period. The goal is to explore relationships between patient acuity, incidents, staffing levels, overtime, and length of stay, and to generate data‑driven operational recommendations.

## Dataset description

The dataset is a synthetic (fictional) daily‑level dataset representing a behavioral health unit. Each row corresponds to a single day.

**Columns:**

- `date`: Calendar date of the observation.
- `weekday`: Day of the week (e.g., Monday, Tuesday).
- `patient_count`: Number of patients on the unit that day.
- `avg_acuity`: Average patient acuity on a 1.0–5.0 scale.
- `incidents`: Number of behavioral incidents recorded that day.
- `staff_on_shift`: Total number of staff scheduled on the unit.
- `overtime_hours`: Total overtime hours used that day.
- `restraints`: Number of restraint events.
- `elopements`: Number of elopement events.
- `avg_length_of_stay`: Average length of stay (in days) for patients on the unit.

## Key questions answered

- How does **average daily acuity** relate to **behavioral incidents**?
- Are **staffing levels** aligned with **acuity and incident volume**?
- Is there a relationship between **overtime_hours** and **incidents**?
- Do certain **weekdays** show consistently higher incident rates?

## Tools used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Key findings

- Higher **average acuity** days tend to have **more incidents**, suggesting increased risk on high‑acuity days.
- On some high‑acuity days, **staffing levels do not increase proportionally**, indicating potential under‑staffing.
- **Overtime_hours** is often higher on days with more incidents, suggesting reactive staffing and possible staff strain.
- Certain weekdays show **higher average incidents**, while weekends tend to be calmer.

## Operational recommendations

- Increase **baseline staffing** on historically high‑acuity and high‑incident days.
- Use **acuity and incident trends** to forecast staffing needs rather than relying primarily on overtime.
- Focus **de‑escalation training and support** on high‑risk days and shifts.
- With real data, extend the analysis to include **shift‑level patterns**, **staff mix**, and **intervention effects**.

## How to run the notebook

1. Download the notebook:  
   `behavioral_health_unit_operational_insights.ipynb`
2. Download the dataset:  
   `behavioral_health_unit_daily_operations.csv`
3. Open the notebook in **Google Colab** or Jupyter.
4. Upload the CSV file to the same environment.
5. Run the cells from top to bottom to reproduce the analysis and visualizations.

