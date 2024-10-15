During summer 2023, I participated in 'Data Science for All,' a fellowship for data professionals in underrepresented groups. As part of the fellowship, my team of four designed a research project to address a question of our choosing. This Github folder includes my personal code and our final presentation. Our team won an award for being one of the top four projects out of over thirty teams. We worked with data from Centers for Medicare & Medicaid Services (CMS). CMS penalizes hospitals with high readmission rates by paying them up to 3% less for inpatient stays. Of course, sicker patients are more likely to be readmitted. Thus, CMS adjusts for ‘risk factors,’ including age and comorbidities. Our question: Should the CMS also adjust for race? Our first model mimics the current CMS risk adjustment. This model uses age and comorbidities to predict readmission rate. Our second model also includes race as a predictive variable. We found that including race had no impact on predicting readmission rate. Upon further investigation, we found that race is picked up by features such as percent of patients with diabetes and percent of patients dual enrolled in Medicaid. CMS is capturing the effect of race on readmission rate indirectly. 
