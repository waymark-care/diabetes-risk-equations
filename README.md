# Risk Equations for Complications Of type 2 Diabetes (RECODe) 

Type 2 diabetes mellitus is an increasing cause of morbidity and mortality worldwide. Treatment of type 2 diabetes involves complex decision-making to prevent microvascular and macrovascular complications of diabetes, while minimizing side effects from therapy. Treatment decisions for type 2 diabetes, as for a number of chronic disease conditions, have increasingly been informed by risk equations, which estimate the risk of complications given the demographics, clinical features, and biomarkers of a patient. Treatment decisions using risk calculations to direct therapies for microvascular conditions (e.g., calculating benefit/risk of insulin titration, rather than using the same hemoglobin A1c target for all individuals) has been suggested, with simulation models indicating that such “benefit-tailored therapy” could reduce microvascular complications of type 2 diabetes, complications induced by therapies themselves, and the overall costs of type 2 diabetes treatment. Treatment guidelines for macrovascular risk reduction already recommend clinicians to perform risk calculations as a standard part of lipid management (e.g., to direct therapy to those with a high 10-year risk of myocardial infarction or stroke), but existing equations have been criticized for misestimating risk. The availability of accurate type 2 diabetes risk equations is therefore important to personalize treatment, ensure informed decision-making on the part of both clinicians and patients, and compare the effectiveness and cost-effectiveness of alternative treatment guidelines.

Recent studies of type 2 diabetes outcomes revealed that commonly-used risk equations misestimate the risk of both microvascular and macrovascular complications among diverse participants in recent randomized trials and longitudinal cohort studies. The poor calibration of existing type 2 diabetes risk equations may be partly because available risk equations were developed from older cohorts not exposed to modern trends in risk, prevention, diagnosis, and treatment.

The development and validation of updated type 2 diabetes risk equations is potentially facilitated by the release of newer large-scale data from trials that provide a unique opportunity to develop equations for type 2 diabetes complications and mortality among modern populations with contemporary risk and treatment exposures. Here, answering a call from the U.S. Centers for Disease Control and Prevention [ http://bit.ly/2m9Pw4g ], we sought to develop and validate an updated series of risk equations for both microvascular and macrovascular complications of type 2 diabetes, using individual participant data recently released from a large study of diabetes complications, the Action to Control Cardiovascular Risk in Diabetes (ACCORD) trial. After we developed risk equations from the ACCORD trial [ https://github.com/sanjaybasu/t2dmriskeqns/blob/master/accorddevelopment.R ], we validated the equations using individual participant data from people who developed type 2 diabetes in the Diabetes Prevention Program Outcomes Study (DPPOS, which provided microvascular outcome data) [ https://github.com/sanjaybasu/t2dmriskeqns/blob/master/dpposvalidation.R ], and all subjects in the Action for Health in Diabetes trial (Look AHEAD, which provided macrovascular outcome data) [ https://github.com/sanjaybasu/t2dmriskeqns/blob/master/lookaheadvalidation.R ]. We additionally compared the newly-developed risk equations to older equations from the UK Prospective Diabetes Study Outcomes Model 2 (for microvascular and macrovascular outcomes) and the ACC/AHA Pooled Cohort Equations (for macrovascular outcomes) [ https://github.com/sanjaybasu/t2dmriskeqns/blob/master/ukpdsacc%20v3.R ].

Code to implement an automated GUI calculator (using the Shiny app for R) is available in either US/conventional units [ https://github.com/sanjaybasu/t2dmriskeqns/blob/master/app.R ] or SI units [ https://github.com/sanjaybasu/t2dmriskeqns/blob/master/appSI.R ], and implemented online [ https://sanjaybasu.shinyapps.io/recode/ ].

For additional reading, please see:

1 Basu S, Sussman JB, Berkowitz SA, Hayward RA, Yudkin JS. Development and validation of Risk Equations for Complications Of type 2 Diabetes (RECODe) using individual participant data from randomised trials. Lancet Diabetes Endocrinol 2017; 5: 788–98.
https://www.sciencedirect.com/science/article/pii/S2213858717302218

2 Basu S, Sussman JB, Berkowitz SA, et al. Validation of Risk Equations for Complications of Type 2 Diabetes (RECODe) Using Individual Participant Data From Diverse Longitudinal Cohorts in the U.S. Diabetes Care 2018; 41: 586–95.
http://care.diabetesjournals.org/content/41/3/586

Sanjay Basu, M.D., Ph.D.1,2*, Rodney A. Hayward, M.D.3,4, Jeremy B. Sussman, M.D., M.S.3,4, Seth A. Berkowitz, M.D., M.P.H.5,6, John S. Yudkin, M.D.7

1 Department of Medicine, Center for Population Health Sciences and Center for Primary Care Outcomes Research, Stanford University
2 Center for Primary Care, Harvard Medical School
3 Division of General Medicine, University of Michigan
4 Center for Clinical Management Research, Veterans Affairs Ann Arbor Healthcare
5 Division of General Internal Medicine and Diabetes Unit, Massachusetts General Hospital
6 Department of Medicine, Harvard Medical School
7 Division of Medicine, University College London

*Email: basus@stanford.edu

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
