# TDA_Persistent_Homology

**Background:** To provide accurate predictions, current machine learning-based solutions require large, manually labeled training datasets. We implement persistent homology (PH), a topological tool for studying the pattern of data, to analyze echocardiography-based strain data and differentiate between rare diseases like constrictive pericarditis (CP) and restrictive cardiomyopathy (RCM).

**Methods:** Our patient population included those presenting with heart failure due to CP (n=51), RCM (n=47), and patients with no heart failure symptoms (n=53). Longitudinal, radial, and circumferential strains/strain rates for left ventricular segments were processed into persistent image feature vectors. Data was stratified into training (80%) and testing (20%). Using the PH workflow, persistence images (PIs) were collected as the desired topological features. Machine learning through Random Forest (RF) discriminated between 1) CP and RCM and 2) all patients (CP, RCM, and normal). Global longitudinal strain (GLS) was used to create a baseline logistic regression model for comparison.

