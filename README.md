# Foodwill SDG 2 Eurasia Analytics

A data analytics and dashboarding project developed for **Foodwill Charitable Organization (FCO)** to monitor and evaluate progress toward **UN Sustainable Development Goal 2: Zero Hunger** across selected target countries using FAO food security and nutrition indicators.

## Project Overview

This repository contains the end-to-end analytical workflow for a multi-country food security assessment designed to support NGO decision-making. The project focuses on identifying hunger, undernourishment, and child malnutrition trends in selected countries where intervention planning and resource prioritization are critical.

The analytical objective is to transform publicly available food security data into actionable insights through data preparation, statistical analysis, and dashboard-based storytelling. The project is aligned with **SDG 2**, particularly **Targets 2.1 and 2.2**, which focus on ending hunger, improving food security, and addressing malnutrition. :contentReference[oaicite:3]{index=3}

## Problem Context

Foodwill Charitable Organization (FCO) is an NGO working toward hunger reduction and improved food access in vulnerable regions. To support evidence-based interventions, this project evaluates food insecurity conditions across six selected countries:

- Afghanistan
- Nepal
- Bangladesh
- Ukraine
- Republic of Moldova
- Albania

The purpose of the analysis is to identify patterns in food insecurity and malnutrition, compare country-level performance, and support strategic humanitarian planning. :contentReference[oaicite:4]{index=4}

## Dataset

The primary dataset used in this project is:

**Food Security & Nutrition / Suite of Food Security Indicators**  
**Source:** FAO (Food and Agriculture Organization of the United Nations)

### Dataset Characteristics

- Publicly available and sourced from a credible UN-affiliated organization
- Covers food security and nutrition indicators relevant to SDG 2
- Covers the period **2000 to 2023**
- Compiled using contributions from organizations such as **FAO, World Bank, UNICEF, and WHO**
- Designed to support food security monitoring and policymaking :contentReference[oaicite:5]{index=5} :contentReference[oaicite:6]{index=6}

### Key Indicators Used

The project focuses on indicators that directly reflect hunger and nutritional vulnerability, including:

- Prevalence of undernourishment (2.1.1)
- Prevalence of severe food insecurity (2.1.2)
- Prevalence of stunting in children under 5 years of age (2.2.1)
- Prevalence of malnutrition in children under 5 years of age, including wasting and overweight (2.2.2)
- Dietary energy supply used in the estimation of undernourishment

These indicators were selected because they are strongly aligned with FCO’s mission and provide both adult- and child-level insights into food insecurity outcomes. :contentReference[oaicite:7]{index=7} :contentReference[oaicite:8]{index=8}

## Objectives

This repository aims to:

- Build a reproducible analytics workflow for SDG 2 monitoring
- Clean and structure FAO food security data for analysis
- Address data quality issues such as missing values and threshold-coded entries
- Explore temporal and cross-country trends in hunger and malnutrition
- Create an interactive dashboard for communicating findings and supporting policy recommendations

## Data Processing and Preparation

The dataset required substantial preprocessing before analysis and dashboarding. Key preparation steps included:

- Filtering relevant countries and indicators
- Removing redundant or non-analytical metadata columns
- Standardizing formats and data types
- Handling missing values using interpolation and forecasting-based treatment
- Interpreting threshold-style values such as `"<0.1"`
- Reviewing outliers for contextual relevance rather than removing them blindly
- Standardizing year intervals for consistency
- Normalizing variables to support fair cross-country comparison

The preprocessing pipeline was designed to preserve analytical integrity while making the dataset suitable for downstream statistical analysis and visualisation. :contentReference[oaicite:9]{index=9} :contentReference[oaicite:10]{index=10}

## Analytical Approach

This project follows a decision-support analytics framework combining data cleaning, descriptive analysis, and visual intelligence.

### Methods used include

- Data cleaning and transformation
- Missing-value treatment
- Outlier assessment
- Descriptive statistical analysis
- Country-level comparison
- Trend analysis over time
- Correlation analysis
- Dashboard-based visual analytics

The broader goal is not only to report values, but to generate interpretable evidence on which countries appear most vulnerable, which indicators are improving or worsening, and where NGO intervention may have the highest impact. :contentReference[oaicite:11]{index=11}

## Quantitative Insights Considered

The project incorporates descriptive and inferential analysis to understand food security conditions across target countries. This includes:

- Measures of central tendency such as mean and median
- Measures of dispersion such as standard deviation and coefficient of variation
- Cross-country comparison of dietary energy supply
- Correlation analysis between dietary energy supply, undernourishment, and stunting

Examples from the preliminary quantitative analysis show substantial variation across countries, including high instability in Afghanistan’s food supply and stronger stability in Moldova. Correlation results also suggest an inverse relationship between dietary energy supply and undernourishment/stunting. :contentReference[oaicite:12]{index=12}

## Tools and Technologies

This project uses a combination of analytics and visualisation tools:

- **Python** — data cleaning, interpolation, preprocessing, and statistical analysis
- **Excel** — manual inspection, validation, and exploratory review
- **PowerBI** — forecasting, dashboard design, and interactive visualisation

These tools were selected to balance automation, transparency, and effective communication of insights. :contentReference[oaicite:13]{index=13}

## Expected Outputs

This repository is designed to support the creation of:

- Cleaned analytical datasets
- Processed indicator tables
- Country comparison views
- Time-series trend visualisations
- SDG 2 monitoring dashboards
- Evidence-based recommendations for NGO intervention planning

## Data Quality Considerations

Several data quality issues were identified during the project:

- Missing values across selected indicators
- Threshold-based reporting such as `"<0.1"`
- Inconsistent time intervals in some observations
- Outliers reflecting possible real-world instability rather than data entry errors

These issues are analytically important because they can distort food insecurity estimates and weaken decision-making quality if not handled carefully. For that reason, the project adopts structured preprocessing and context-aware treatment of incomplete and irregular observations. :contentReference[oaicite:14]{index=14} :contentReference[oaicite:15]{index=15}

## References

- FAO. *Food Security & Nutrition / Suite of Food Security Indicators*
- United Nations. *Sustainable Development Goal 2: Zero Hunger*
- Dong, Y., & Peng, C. J. (2013). *Principled missing data methods for researchers*
- Ibrahim, E., Shouman, M. A., Torkey, H., & El-Sayed, A. (2021). *Handling missing and outliers’ values by enhanced algorithms for an accurate diabetic classification system*

## License

This project is intended for **academic and educational use** only.
