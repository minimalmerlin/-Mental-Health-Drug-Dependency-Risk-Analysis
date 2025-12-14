🧠 Mental Health & Drug Dependency Risk Analysis
📌 Project Overview
This project analyzes the correlation between various mental health disorders and the risk of developing illicit drug dependency. Using data from Our World in Data, the analysis challenges the common perception that depression is the primary driver of drug dependency.

The goal was to move from exploratory data analysis to an explanatory data story, highlighting specific high-risk groups to inform better prevention strategies.

🔍 Key Insights
Impulse Control is Critical: Disorders related to impulse control and behavior (e.g., Intermittent Explosive Disorder, ADHD) carry the highest risk, with an Odds Ratio between 5.2 and 6.3.

Context Matters: While depression and anxiety are significant, their statistical risk factor is considerably lower compared to behavioral disorders.

Clustering: Grouping the 18 distinct diagnoses into three categories (Behavior, Mood, Anxiety) revealed a clear visual hierarchy of risk.

📊 Visualisation
(Here you can insert the screenshot of your chart)

Interactive Dashboard: [Link to your Tableau Public Dashboard]

🛠 Methodology
Data Sourcing: Raw data extracted from Our World in Data (Mental Health Risk Factors, 2010).

Data Cleaning (Excel): Removed irrelevant columns (Codes, unused years) and standardized entity names.

Data Enrichment: Categorized the medical entities into three distinct clusters to reduce cognitive load:

🔴 Behavioral/Impulse (High Risk)

🟡 Mood Disorders (Medium Risk)

⚪ Anxiety & Trauma (Lower Relative Risk)

Visualization: Designed a horizontal bar chart focusing on "preattentive attributes" (color & position) to guide the viewer's eye to the key insight immediately.

🧰 Tools Used
Microsoft Excel: Data Pivot, Cleaning, and Categorization.

Tableau Public: Final data storytelling and visualization.

Python (Optional): Used for initial data validation.

📂 Repository Structure
data/: Contains the raw and cleaned CSV files.

images/: Screenshots of the analysis.

README.md: Project documentation.

📬 Author
Merlin Mechler
	•	https://www.linkedin.com/in/merlin-mechler/
	•	Project created as part of the Midscale Institute portfolio.
