




# Project Background
This analysis focuses on employee productivity and morale during the tranistion to remote work. The data was collected through surveys administered in New South Wales, Australia, during two key phases: August-September 2020 and March-April 2021. As a data analyst working with this dataset, I was tasked with evaluating the impact of remote work on employees' productivity, morale, and work-life balance to inform post-pandemic policies.

Insights and recommendations are provided on the following key areas:

- **Employee Productivity:** Trends in self-reported productivity levels.
- **Morale Challenges:** The ongoing effects of isolation and collaboration difficulties.
- **Work-Life Balance:** Effects of reduced commuting time on work-life balance.
- **Employee Preferences:** Shifts in preference for remote, hybrid, or in-office work models. 

The SQL queries used to inspect and clean the data for this analysis can be found here [link].

Targed SQL queries regarding various business questions can be found here [link].

An interactive Tableau dashboard used to report and explore sales trends can be found here [link].



# Data Structure & Initial Checks

The dataset consists of two main tables: one for survey responses and one for employee demographics. There are a total of 1,200 records across both datasets. The description of each table is as follows:
- **Survey Responses:** Contains self-reported data on productivity, morale, and work preferences from employees.
- **Employee Demographics:** Includes basic information about each respondent (e.g., job role, industry, tenure).

[Entity Relationship Diagram here]



# Executive Summary

### Overview of Findings

Employee productivity showed slight improvements in 2021, especially in managerial roles. However, morale remains a significant challenge, with over 25% of respondents citing issues like isolation and poor collaboration. While work-life balance improved due to reduced commuting, employees expressed a preference for hybrid work models, indicating a need for more flexible policies.

![remote_work_report](https://github.com/user-attachments/assets/de8b6e9b-d880-41d8-b65b-39312233d569)



# Insights Deep Dive
### Employee Productivity:

* **Main insight 1.** Productivity slightly increased from 2020 to 2021, with managers reporting the most significant improvements.
  
* **Main insight 2.** Employees in higher roles saw more significant productivity gains, possibly linked to increased flexibility.
  
* **Main insight 3.** Despite overall improvements, a portion of employees still struggled with focus and task completion, indicating room for targeted support.
  

[]


### Morale Challenges:

* **Main insight 1.** Isolation and collaboration difficulties were consistent challenges for over 25% of employees across both years.
  
* **Main insight 2.** Employees in roles requiring frequent teamwork experienced more pronounced morale issues, suggesting a need for virtual team-building efforts.
  
* **Main insight 3.** While communication tools were helpful, their overuse led to digital fatigue for some employees.
  

[Visualization specific to category 2]


### Work-Life Balance:

* **Main insight 1.** Reduced commuting time significantly improved work-life balance for most employees.
  
* **Main insight 2.** However, employees expressed that a complete shift to remote work led to challenges in separating personal and professional lives.
  
* **Main insight 3.** Employees expressed a preference for hybrid models to maintain a work-life balance while fostering collaboration.
  

[Visualization specific to category 3]


### Employee Preferences:

* **Main insight 1.** A significant portion of employees preferred a hybrid work model, blending both remote and in-office work.
  
* **Main insight 2.** Despite the preference for hybrid work, a smaller group favored full-time remote work due to peronal reasons.
  
* **Main insight 3.** The preference for hybrid models was most prevalent among employees in roles that required both independent work and team collaboration.
  

[Visualization specific to category 4]



# Recommendations:

Based on the insights and findings above, we would recommend the following to key stakeholder teams: 

* **HR Teams:** Address morale challenges by implementing virtual team-building activities and ensuring communication tools are used effectively to prevent digital fatigue. **Recommendation or general guidance based on this observation.**
  
* **Managers:** Offer flexibility to employees by promoting hybrid work models and focusing on support for those struggling with productivity. **Recommendation or general guidance based on this observation.**
  
* **Workplace Strategy Teams:** Use the insights on work-life balance and employee preferences to design hybrid models that cater to different roles and needs. **Recommendation or general guidance based on this observation.**
  
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1: Survey responses were self-reported, so some data may be subject to personal bias or inaccuracies.
  
* Assumption 2: The 2020 and 2021 survey data was compared directly, assuming that external factors influencing productivity and morale were similar across both periods.
  
* Assumption 3: Missing data points, particularly in the "morale challenges" section, were filled using the most common responses from other employees.
