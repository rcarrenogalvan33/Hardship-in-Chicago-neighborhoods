# Hardship-in-Chicago-neighborhoods

Chicago Socioeconomic Analysis: Predicting Hardship with GAMs
Project Overview

This project analyzes the relationship between per capita income, poverty rates, and overall community hardship across all 77 Chicago Community Areas. The goal was to build a highly accurate predictive model to identify neighborhoods most at risk for socioeconomic distress, supporting evidence-based policy evaluation.
Key Technical Achievements

    97% Predictive Accuracy: Achieved an Adjusted R2 of 0.968, meaning the model explains nearly 97% of the variation in hardship across the city.

    Advanced Statistical Modeling: Utilized Generalized Additive Models (GAMs) to capture non-linear relationships that traditional linear regressions often miss.

    Model Validation: Performed rigorous diagnostic checks (basis dimension checks and residual analysis) to ensure the model was flexible enough to follow complex data patterns without bias.

The Research Journey: Why GAMs?

In this analysis, I moved through several modeling stages to find the most accurate "fit" for Chicago's unique economic landscape:

    Linear Regression: Provided a baseline, but struggled to capture "tipping points" where hardship spikes as income drops.

    Polynomial Regression: Improved accuracy but was too "stiff" to adapt to local neighborhood variations.

    The Optimized GAM: By adjusting the "wiggle room" (k) for Income to 10, I successfully modeled the complex, non-linear reality of Chicago's economy while maintaining a clean "health check" (all diagnostic p-values >0.05).

Data Source

    Chicago Data Portal: Public Health Statistics (Socioeconomic Indicators) for 2008–2012.

Technical Skills Used

    Language: R.

    Libraries: tidyverse (Data Cleaning), mgcv (Statistical Modeling).

    Frameworks: Theory of Change and evidence-based evaluation.
