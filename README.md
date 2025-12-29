# Drug-Drug-Interaction-Project
As a **Pharm D candidate**, I recognize that manual medication reviews are prone to human error. This project is a **computational prototype** designed to automate the detection of dangerous Drug-Drug Interactions (DDIs) in patient datasets.

By simulating clinical data and applying **Python (Pandas)** logic, this tool identifies high-risk combinations (e.g., *Warfarin + Ciprofloxacin*) and visualizes the prevalence of these risks in a hospital population.

## ⚙️ How It Works
The script follows a three-step pipeline:
1.  **Data Simulation:** Generates a mock dataset representing patient demographics and medication history.
2.  **Interaction Logic:** Scans the dataset for specific contraindicated pairs based on clinical pharmacology rules.
3.  **Risk Stratification:** Classifies patients into `High`, `Medium`, or `None` risk categories and generates a distribution graph.
Sample Output
The tool produces a statistical summary of the patient population:
> Alert: 40.0% of patients are at High Risk of DDI.
It also generates a bar chart visualizing the distribution of risk across the cohort, aiding in rapid decision-making for Antimicrobial Stewardship teams.
Future Scope (Research Goals)
This project is the foundation for my transition into **Computational Epidemiology**. My goal is to expand this framework to:
* Integrate real-world genomic data.
* Predict **Antimicrobial Resistance (AMR)** patterns using machine learning.
* Model transmission dynamics of resistant pathogens in hospital settings.
