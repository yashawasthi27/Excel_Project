# Excel_Project
Dynamic Excel dashboard to analyze and visualize data domain job salaries. Features interactive filters for job title, country, and type, with real-time KPIs.
## Features

* **Dynamic Filters:** Users can filter the entire dashboard in real-time using three dropdown menus:
    * Job Title (e.g., Data Engineer, Data Scientist)
    * Country
    * Employment Type (e.g., Full-time, Contractor)
* **Interactive Visualizations:**
    * **Salary by Job Title:** A bar chart that updates to show salary ranges for related roles.
    * **Salary by Location:** A choropleth map that visualizes data geographically.
    * **Salary by Type:** A bar chart comparing salaries across different employment types.
* **Custom KPIs:** Three main key performance indicators (KPIs) automatically update based on the selected filters:
    * **Median Salary:** Calculates the median salary for the filtered criteria.
    * **Top Job Platform:** Identifies the most common platform for the job postings.
    * **Job Count:** Shows the total number of job listings that match the filters.

---

## Technical Details

This dashboard was built in Excel without plugins, relying on modern formulas and features:

* **Formulas & Functions:** The dashboard's logic is driven by a combination of advanced functions, including:
    * `XLOOKUP`
    * `FILTER`
    * `SORT`
    * `COUNTIFS`
    * `MEDIANIF`
    * `IF`
    * `ISNUMBER`
    * `SUBSTITUTE`
* **Data Validation:** Used to create the dynamic, searchable dropdown filters.
* **Conditional Formatting:** Applied to visualizations for better readability.
* **Named Ranges:** Used extensively for clean formulas and easy maintenance.
* **Performance:** Formulas were structured to ensure the dashboard remains fast and responsive despite complex calculations.
