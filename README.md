# BIMarathon2022

BodyFat dataset analysis and comparison with BMI range categorizing 

Requester(s): Marina Manulik
Date: Jun 30, 2022
Audience (intended users): public
Requested go live date: August 30, 2022


Problem Statement
How categorizing of body fat corelates with categorizing of BMI index


Business Justification (Benefits/ROI)

The analyses of the dataset with dimensions Fat Rage, Health Range, Weight Status (BMI)and facts(metrics) - Density, Age,	Weight,	Height,	Neck, Chest,Abdomen, Hip,	Thigh,	Knee,	Ankle,	Biceps,	Forearm,	Wrist. Success will be measured by showing if there are any notable tendency between Fat Rage, Health Range, Weight Status (BMI.

Note.
Adult body far percentage = (1.20 * BMI) + (0.23 * age) – (10.8 *sex) – 5.4 
Where sex = 0 for females and 1 for males

In a given dataset next columns was added in MySQL workbench:

 Siri index = (495 /density) - 450)
 Brozek index = (4.57 /density) - 4.142) * 100)
 BMI = (weight * 703) / (height * height)
 Weight status (BMI) - underweight/healthy weight/overweight/obesity
 fat_range - dangerously low/poor/good/excellent/dangerously heigh
 health_range = non-healthy/ healthy



Data Source - 
SOURCE:
The data was provided by Dr. A. Garth Fisher, Human
Performance Research Center, Brigham Young University, Provo, Utah
84602, who gave permission to freely distribute the data and use them
for non-commercial purposes.  Reference to the data is made in Penrose,
et al. (1985).
Body Fat Prediction Dataset
https://www.kaggle.com/datasets/fedesoriano/body-fat-prediction-dataset

Body fat percentage chart
https://www.medicalnewstoday.com/articles/body-fat-percentage-chart#men

Body mass index as a measure of body fatness: age- and sex-specific prediction formulas
https://www.cambridge.org/core/journals/british-journal-of-nutrition/article/body-mass-index-as-a-measure-of-body-fatness-age-and-sexspecific-prediction-formulas/9C03B18E1A0E4CDB0441644EE64D9AA2

Body fat percentage
https://en.wikipedia.org/wiki/Body_fat_percentage

Accuracy of Siri and Brozek equations in the percent body fat estimation in older adults
https://pubmed.ncbi.nlm.nih.gov/21085903/


