# Project Title
## Movie Market Analysis

## Overview
New company seeks to venture into movie industry by establishing its own movie studio although with no prior experience of film production and market strategy. The given project utilizes exploratory data analysis for insights to make better decisions. 

Based on historical data of Box Office Mojo, IMDb, TMDB, The Numbers, and Rotten Tomatoes, we performed high-level exploratory data analysis (EDA) to determine the tendencies of the box office performance, production budgets, and geographic distribution of revenue. This is aimed at translating these insights into practical, follow-up advice on the kind of films to create, which viewers are to reach, and how to find the right balance in placing resources.

The analysis is intentionally non-technical and business-focused, making the results accessible to stakeholders and suitable as a strategic foundation for launching a new movie studio.

## Business Understanding
The objective of this project is to support the company’s decision to launch a new movie studio by using data-driven insights. Specifically, this analysis aims to:
.To identify and prioritize genres based on revenue performance
.To determine audience ratings profiles to target 
.To analyze the effect of production cost to revenue
.To evaluate revenue distribution but geography to determine top performing regions

## Data Understanding and Analysis
The data utilized in this project was carefully selected from multiple reputable sources to gain insights into the movie industry's landscape. These datasets cover various critical aspects, including box office performance, production budgets, genres, and audience/critic ratings. The datasets include:

1. **Movie Gross**: Contains information about box office gross revenue.
2. **TMDB Movies Data**: Includes metadata such as movie titles, genres, and other industry-specific attributes.
3. **Movie Budgets**: Details the production budgets and resulting worldwide gross income, helping in ROI analyses.
4. **Rotten Tomatoes Movie Information**: Provides critic reviews and audience scores, valuable for understanding rating profiles.
5. **Reviews Data**: Consists of textual reviews for sentiment and critical analysis.

### Data Loading
The datasets have been imported using the Pandas library from `.csv` and `.tsv` files. Preliminary inspection was conducted to verify the structure, content, and completeness:
- Each dataset was loaded and checked for null values or inconsistencies.
- Summary statistics (count, mean, etc.) were generated to understand initial trends and anomalies.

### Data Analysis Approach
Data analysis conducted in the notebook centers around the following goals:
1. **Exploratory Data Analysis (EDA)**:
   - Using visual tools (e.g., Matplotlib) for trends analysis such as revenue by genre and the relationship between production budgets and gross revenue.
   - Statistical methods were applied to analyze the distribution of revenue across geographies.
   
2. **Insights Extraction**:
   - Identification of high-performing genres based on revenue data.
   - Classification of audience and critic preferences through analysis of scoring metrics.
   - Calculation of ROI to determine the influence of production budgets on profitability metrics.

The analysis is critical in distributing resources efficiently and crafting evidence-backed strategies. Using a multifaceted approach ensures the results are robust and actionable for business decision-making.

### Tools Used
- **Pandas**: Data cleaning, manipulation, and exploration.
- **Matplotlib**: Generating plots for visual insights.
- **SQLite**: Manage and query data if necessary (not explicitly used but imported for utility).


## Conclusion

- Prioritize genres that consistently deliver large box office revenues for commercial-scale investments such as Animation,     Fantasy and Family films consistently generate the highest revenues. 

- Audience reception and rating is an important signal for commercial performance of genres.

- For investments, the new company should focus producing their movies in high-revenue regions which show consistent box office returns . This will be done through prioritizing marketing, distribution and content tailored to these audiences. Strategically, avoid low-revenue regions.

- Additionally, adapt movie genres based on what resonates in top-performing regions and can also consider co-production or partnerships in strong markets to minimize risks and maximize reach

- Investing in moderate-budget films may provide better risk-adjusted returns than consistently funding very high budget productions. That high-budget films don’t necessarily mean that the ROI will be high.