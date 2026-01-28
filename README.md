# FinTech Adoption and Its Impact on Traditional Banking in Nepal: A Primary Survey Analysis

**Nandika Thapa**  
Finance & Economics Portfolio | [LinkedIn](https://www.linkedin.com/in/nandika-thapa) | nandikathapa4@gmail.com  

## Overview
This independent research project examines the drivers, user satisfaction, barriers, and behavioral impact of FinTech services in Nepal's banking sector. Based on original primary data collected via an online survey (N=110+ respondents, diverse demographics), the study employs econometric and statistical methods to quantify FinTech's role in reducing reliance on physical branches and promoting financial inclusion in a developing market context.

**Relevance to Graduate Studies**: The analysis bridges empirical economics, financial innovation, and development finance—areas central to Luxembourg's position as a European financial hub and our programs' focus on quantitative finance, digital transformation, and sustainable economic systems.

## Methodology
- **Data Collection**: Structured questionnaire covering demographics, usage frequency, service types, satisfaction (Likert scale), adoption drivers, challenges, and perceived branch reduction.
- **Tools & Techniques**:
  - Python (pandas for data wrangling, statsmodels for modeling)
  - Visualizations: seaborn/matplotlib (bar plots, pie charts, heatmaps)
  - Inferential statistics: Chi-square tests of independence
  - Econometric modeling: Logistic regression (addressing quasi-separation via regularization)
- **Key Challenge Addressed**: Quasi-complete separation in logistic models mitigated through penalized estimation, yielding interpretable odds ratios.

## Key Findings
- **High Adoption & Satisfaction**: Daily/weekly usage prevalent; satisfaction scores predominantly 4–5/5.
- **Behavioral Impact**: ~80% of respondents reported significant/some reduction in physical bank visits due to FinTech convenience (24/7 access) and speed.
- **Drivers & Barriers**: Top drivers = convenience and faster transactions; major challenges = hidden fees, poor connectivity, security concerns.
- **Statistical Results**:
  - Chi-square: No significant association between student status and branch reduction (p=0.786).
  - Logistic regression: Strong baseline probability of reduced visits (intercept OR ≈7.54, p<0.001); predictors dominated by baseline prevalence after regularization.
- **Comparative Insights**: Nepal's context contrasted with regional leaders (India's UPI, Bangladesh's bKash), highlighting regulatory, infrastructure, and trust gaps.

## Visualizations
![Occupation Distribution](occupation_pie.png)  
*Pie chart: Respondent occupations—students and professionals dominate.*

![Branch Reduction Impact](branch_reduction.png)  
*Bar plot: Majority report significant reduction in physical bank visits.*

![Top Adoption Drivers](adoption_drivers.png)  
*Ranked drivers: Convenience leads overwhelmingly.*

![Top Challenges](top_challenges.png)  
*Challenges: Hidden fees and connectivity most cited.*

(Include 3–4 key plots with captions; ensure high resolution.)

## Implications & Recommendations
- FinTech augments rather than replaces traditional banking in Nepal—hybrid models recommended.
- Policy priorities: Improve rural connectivity, enhance transparency/security, foster bank-FinTech collaboration.
- Future research: Longitudinal studies or larger samples to address generalizability.

## Files
- Interactive Jupyter Notebook: [FinTech_Survey_Analysis_Nepal.ipynb](FinTech_Survey_Analysis_Nepal.ipynb)
- Raw data: fintech_responses.csv (anonymized)

This project reflects self-directed research initiative, strong quantitative skills (Python, econometrics), and ability to derive policy-relevant insights from primary data—qualities we value highly in applicants to our Economics & Finance Master's programs.

Last updated: January 2026
