# compensation-benchmarking-dashboard
Compensation benchmarking dashboard analysing CTC, fixed pay, variable pay, and salary distribution across job titles, departments, levels, and locations using Excel and Power BI.
Compensation Benchmarking Dashboard
Project Overview

This project focuses on employee compensation benchmarking, providing insights into CTC distribution, the mix of fixed and variable pay, and pay differences across job roles, departments, levels, and locations.
The dashboard helps HR and management teams evaluate pay competitiveness and internal equity.

Tools Used

Microsoft Excel – data cleaning and preparation

Power BI – data modelling, DAX calculations, and dashboard development

Data Preparation (Excel)

Generated employee-level HR data (ID, name, department, job title, level, location, fixed pay, variable pay, total ctc, industry benchmark, difference%, variable pay%, fixed pay%, benchmark gap ).

Total CTC is calculated using the following logic:
=SUM(G2+H2)

difference% is calculated using the following logic:
=(I2-J2)/J2

variable pay% is calculated using the following logic:
=[@[Variable Pay]]/[@[Total CTC]]

Fixed pay %is calculated using the following logic:
=[@[Fixed Pay]]/[@[Total CTC]]

Benchmark gap is calculated using the following logic:
=[@[Total CTC]]-[@[Industry Benchmark]]

Key Metrics Tracked

Total employee count

Average CTC

Average fixed pay

Average variable pay

Minimum and maximum CTC

Analysis Breakdown

1. Compensation by Job Title

Comparison of average CTC across Intern, Executive, Analyst, Manager, and Director roles

Highlights pay progression across hierarchy levels

2. Department-Level Benchmarking

Average CTC comparison across IT, Finance, HR, Sales, and Marketing

Helps identify departments with higher compensation allocation

3. Fixed vs Variable Pay Structure

Analysis of salary composition by role

Supports evaluation of incentive-heavy vs fixed-pay roles

4. Location-Based Pay Comparison

Average CTC mapped by employee location

Identifies regional compensation differences

Key Insights Enabled

Senior roles show higher fixed-pay dominance, while mid-level roles have higher variable components

IT and Finance departments lead in average compensation levels

Location-based salary variation highlights cost-of-living impact

Clear visibility into pay bands supports compensation planning

Business Value

Supports salary benchmarking and pay structure reviews

Helps ensure internal pay equity

Assists HR in budgeting and compensation strategy

Enables data-driven compensation decisions

Notes

The dataset is simulated for learning and portfolio demonstration.

The dashboard structure reflects real-world HR compensation and MIS reports.
