# pbc

###Project Goal Analyze primary biliary cirrhosis (PBC) data using various methods.

### Data description

Primary biliary cirrhosis (PBC) is a rare but fatal chronic liver disease of unknown cause with a prevalence of about 50-cases-per-million population. It generally strikes women between the ages of 40 and 60, but it has been diagnosed outside of this age range as well as in men. There is currently no known cure for PBC, but liver transplantation is now a common treatment. The clinical trial in Primary Biliary Cirrhosis (PBC) of the liver was conducted between 1974 and 1984 by Mayo Clinic. For that analysis, disease and survival status as of July, 1986, readings were recorded for as many patients as possible.
This is a double blinded experiment of a total of 424 PBC patients.
A randomized placebo controlled trial of the drug D-penicillamine is given to the patients.
Sources of Data
University of Massachusetts Amherst
https://www.umass.edu
Specific: https://www.umass.edu/statdata/statdata/data/pbc.txt
NAME: PBC Data (PBC.DAT)
SIZE: 418 observations, 20 variables
SOURCE: Counting Processes and Survival Analysis by T. Fleming & D. Harrington, (1991), published by John Wiley & Sons.
Variable Description
Case number
Survival Time -The number of days between registration and the earlier of death, liver transplantation, or study analysis time in July, 1986.
Censoring - 1 if X is time to death, 0 if time to censoring
Treatment - Treatment Code, 1 = D-penicillamine, 2 = placebo.
Age - Age in years. For the first 312 cases, age was calculated by dividing the number of days between birth and study registration by 365.
Gender - 0 = male, 1 = female.
Presence of ascites - 0 = no, 1 = yes.
Presence of hepatomegaly - 0 = no, 1 = yes.
Presence of spiders - 0 = no, 1 = Yes.
Presence of edema - 0 = no edema and no diuretic therapy for edema; 0.5 = edema present for which no diuretic therapy was given, or edema resolved with diuretic therapy; 1 = edema despite diuretic therapy
Serum bilirubin - in mg/dl.
Serum cholesterol - in mg/dl.