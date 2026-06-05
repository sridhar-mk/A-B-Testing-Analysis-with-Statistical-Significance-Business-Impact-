A/B Testing Analysis with Statistical Significance & Business Impact
Overview

A/B testing is widely used to evaluate product and marketing changes before deployment. However, relying solely on aggregate conversion metrics can lead to incorrect business decisions.

This project analyzes an experiment conducted on 294,000+ users to determine whether a new landing page improves conversion performance. Beyond traditional hypothesis testing, the analysis investigates market-level behavior, estimates financial impact, and examines the presence of Simpson's Paradox to ensure accurate decision-making.

Business Problem

A company introduced a new landing page with the goal of increasing user conversions.

Before rolling out the page to all users, the business needed to answer three critical questions:

Does the new page improve conversion rates?
Are observed differences statistically significant?
What is the financial impact of deploying the new page?

The objective was to make a data-driven deployment decision while minimizing potential revenue loss.

Dataset
Scale
294,000+ users
Control Group (Existing Landing Page)
Treatment Group (New Landing Page)
Multiple geographic markets
Key Metrics
Conversion Rate
Lift Analysis
Statistical Significance
Revenue Impact
Market-Level Performance
Project Objectives
Compare conversion performance between control and treatment groups
Perform hypothesis testing for statistical significance
Calculate business impact of the experiment
Investigate market-level differences
Detect and analyze Simpson's Paradox
Provide a deployment recommendation
Methodology
Step 1: Data Cleaning & Validation
Removed duplicate users
Verified treatment assignments
Checked experiment integrity
Validated conversion records
Step 2: Conversion Analysis

Measured:

Control Conversion Rate
Treatment Conversion Rate
Absolute Lift
Relative Lift
Step 3: Hypothesis Testing

Performed statistical testing to evaluate whether observed differences were significant or due to random variation.

Step 4: Market-Level Analysis

Segmented results across three major markets:

United States
Canada
United Kingdom
Step 5: Simpson's Paradox Investigation

Compared aggregate results with segmented market performance to identify hidden patterns that could lead to misleading conclusions.

Step 6: Revenue Impact Assessment

Estimated the financial consequences of deploying the treatment page at scale.

Key Findings
Overall Experiment Results
Metric	Control	Treatment
Conversion Rate	12.04%	11.88%
Difference	-0.16 Percentage Points	


The new landing page generated a lower conversion rate than the existing page.

Market-Level Results
United States
Treatment underperformed by 0.22 percentage points
Canada
Treatment underperformed by 0.69 percentage points
United Kingdom
Minor performance variation observed

The treatment page underperformed in the two largest user markets.

Statistical Conclusion

Hypothesis testing indicated insufficient evidence that the new page improved performance.

The observed results suggested that deploying the treatment would likely reduce overall conversions rather than increase them.

Simpson's Paradox Analysis

Aggregate results alone did not fully explain experiment performance.

Segment-level analysis revealed important differences across markets, highlighting the importance of examining subgroup behavior before making deployment decisions.

This prevented potentially misleading conclusions that could have resulted from relying solely on overall conversion rates.

Business Impact
Estimated Revenue Impact
Projected revenue loss: ₹4.2 Lakhs
Recommendation

❌ Do Not Deploy New Landing Page

The treatment page produced lower conversion rates and a projected financial loss.

Maintaining the existing landing page was determined to be the most profitable business decision.

Dashboard Features
Experiment Overview
Conversion Funnel Analysis
Control vs Treatment Comparison
Statistical Significance Results
Market Segmentation Analysis
Revenue Impact Assessment
Tech Stack
Programming
Python
Libraries
Pandas
NumPy
SciPy
Statsmodels
Matplotlib
Seaborn
Analytics
Hypothesis Testing
Statistical Inference
Conversion Analysis
Business Impact Modeling
Simpson's Paradox Detection
Project Structure
ab-testing-business-impact-analysis/

├── data/
├── notebooks/
├── reports/
├── screenshots/
├── src/
├── README.md
└── requirements.txt
Key Skills Demonstrated
A/B Testing
Statistical Analysis
Hypothesis Testing
Experimental Design
Business Analytics
Revenue Impact Assessment
Data Storytelling
Decision Science
Final Recommendation

The analysis concluded that the new landing page should not be launched. Although the difference in conversion rates appeared small, scaling the impact across the user base would result in a projected revenue loss of approximately ₹4.2 Lakhs.

This project demonstrates how statistical analysis can be combined with business impact assessment to support data-driven product decisions.
