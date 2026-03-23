# world_happines_expanatory_analysis
Exploratory Data Analysis (EDA) of the World Happiness Report. Investigating the socio-economic factors influencing global happiness levels using Python, Pandas, and interactive visualizations.
🌍 World Happiness Explanatory Analysis (2021)
📖 Introduction
The World Happiness Report is a landmark survey of the state of global happiness. This report continues to gain global recognition as governments, organizations, and civil society increasingly use happiness indicators to inform their policy-making decisions.

Leading experts across fields – economics, psychology, survey analysis, national statistics, health, and public policy – describe how measurements of well-being can be used effectively to assess the progress of nations. This project explores the 2021 dataset to explain personal and national variations in happiness through data science.

🛠️ Technical Stack
The analysis is conducted using Python with a focus on advanced visualization:

Data Manipulation: Pandas, NumPy

Static Visualization: Seaborn, Matplotlib (Heatmaps, Clustermaps, Swarmplots)

Interactive Visualization: Plotly (Choropleth Maps, Animated Plots)

📊 Analysis Roadmap
The project follows a structured Explanatory Data Analysis (EDA) flow:

1. Data Processing
Reading and initial analysis of the 2021 World Happiness dataset.

Cleaning and organizing regional indicators.

2. Global Distributions
Ladder Score Distribution: Visualizing the overall happiness density.

Regional Insights: Comparing happiness levels across different geographical regions using Box and KDE plots.

3. Geographical Mapping (Interactive)
World Map View: An interactive Plotly map displaying Ladder Scores by country.

Generosity Map: Mapping global generosity levels to identify regional patterns.

4. Behavioral & Economic Analysis
Top & Bottom Nations: Identifying the happiest and unhappiest countries in 2021.

Generosity Analysis: Investigating the most and least generous nations and their regional distribution.

5. Relationship Analysis (Multivariate)
Deep dive into how happiness correlates with critical life factors:

Happiness vs. Income (GDP): Does wealth guarantee happiness?

Happiness vs. Freedom: The impact of personal liberty on well-being.

Happiness vs. Corruption: How perception of corruption affects national morale.

6. Correlation & Clustering
Heatmap: Statistical correlation between all features.

Clustermap: Using hierarchical clustering to group countries with similar socio-economic profiles.

📂 Dataset Information
The analysis uses the following data sources from Kaggle:

world-happiness-report-2021.csv

world-happiness-report.csv (Historical data)

population_total_long.csv (World population context)

💡 Conclusion
The final section of the notebook summarizes the key drivers of happiness in 2021, highlighting the unexpected resilience of certain regions and the undeniable link between social support and life satisfaction.

🚀 How to Run
Clone this repository:

Bash
git clone https://github.com/kullanici-adin/world_happines_expanatory_analysis.git
Install required libraries:

Bash
pip install pandas numpy seaborn plotly matplotlib
Open the Jupyter Notebook:

Bash
jupyter notebook

🏁 Conclusion & Final Insights
After a comprehensive explanatory analysis of the 2021 World Happiness Report, several key patterns and insights have emerged regarding global well-being:

1. The Wealth vs. Happiness Paradox
While there is a strong positive correlation between GDP per capita and Ladder Scores, the relationship is not strictly linear. In many developed nations, we observe "diminishing returns," where increases in wealth have a smaller impact on happiness compared to developing nations.

2. The Power of Social Support & Freedom
The analysis shows that Social Support and Freedom to make life choices are often better predictors of long-term happiness than income alone. Countries in Northern Europe (Scandinavia) consistently rank at the top not just due to wealth, but due to high levels of social trust and low perceived corruption.

3. Regional Disparities
Top Performers: Western Europe and North America/ANZ regions continue to lead in happiness scores.

Resilience: Despite economic challenges, certain regions show high Generosity scores, proving that altruism isn't always tied to financial surplus.

Low Scorers: Sub-Saharan Africa and South Asia regions often struggle with lower scores, primarily driven by lower life expectancy and limited access to social safety nets.

4. Corruption's Invisible Tax
The Perception of Corruption shows a significant negative impact on national morale. Even in high-income countries, a high perception of corruption can lead to a visible dip in the overall happiness score, acting as a "happiness-reducer" across all demographics.

5. Summary
Happiness is a multidimensional metric. To improve a nation's well-being, policy-makers should focus not only on economic growth (GDP) but also on fostering social trust, protecting personal freedoms, and investing in public health.
