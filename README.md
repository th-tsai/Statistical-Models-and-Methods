# Statistical Models and Methods

## Introducation

In this repository, I would revisit the coursework form module Statistical Models and Methods. Previously, the coursework required us to use linear models to tackle the problems. This time, I will expand the models using generalised linear model, decision tree and random forest. All coding will bases on Python with relevant packages. This would also be a Python practice because I'm used to code in R before.

## Data

The training and test data set are stored in the Data file.

## Question

You work as a risk analyst for a bank, making lending decisions on loan applications. Data are available on the credit score of 1000 individuals, together with the values of 20 explanatory variables for each individual. The credit score has been determined independently by experts, without reference to the covariates. Interest lies in using these data to build models to explore any association between credit score and the available explanatory variables, and to predict credit scores based on these variables. The models could then be used to assign a credit score to a new loan applicant, to form the basis of a lending decision given the applicant’s data.

### The Tasks

#### (a) 
Using only the TRAINING data, investigate models to explain the relationship between CreditScore and the other variables. That is, CreditScore is to be the response variable, and all other variables are potential explanatory variables. Briefly interpret your models in terms of the association between the explanatory variables and credit scores.

#### (b) 
Use your chosen “best” model(s) from (a) to predict the responses (credit scores) for the individuals in the TEST data set. Compare your predicted responses with the known observed responses from the observations in the Test data, using suitable plots/numerical summaries. What is the mean-squared error of the predictions, and how does this compare to the mean-squared error of the “full” model?

#### (c) 
It is now of interest to classify the individuals from the TEST set into two groups (“bad” risks and “good” risks), using your model’s predicted credit scores. The bank considers “bad” risks to be those with a credit score below 500. Use the following classification rule, based on the predicted credit scores from part (b), to classify the individuals in the TEST set as bad/good risks.

### The Variables

An explanation of the variables in each data set is given below, with (F) signifying factor and (C) signifying a continuous/numerical quantity.

#### Status (F)
Status of current account balance. Levels: ”Negative”,”Small”, ”Large”,”None” (no current account or unknown).

#### Duration (C)
Duration of requested loan in months.

#### History (F)
Status of previous loan history. Levels: ”A” (none, or all paid back in full), ”B” (all at this bank paid in full), ”C” (ongoing loans fully paid so far), ”D” (late payments in past), ”E” (critical delays/defaults in past).

#### Purpose (F)
Purpose of loan. Levels: ”NewCar”,”UsedCar”,”Other”,”Furniture”,”Television”, ”Domestic”,”Repairs”,”Education”,”Training”,”Business”.

#### Amount (C)
Amount requested in Euros.

#### Savings (F)
Balance of savings account. Levels: ”Low”,”Medium”,”Large”,”VeryLarge”,”Unknown”.

#### Employment (F)
Time in current employment. Levels: ”Unemployed”,”Short”,”Medium”, ”Long”,”VeryLong”.

#### Disposable (C)
The monthly repayment installments as a percentage of annual disposable income.

#### Personal (F)
Personal status. Levels: ”M:DivSepMar” (Male, Divorced/Separated/Married), ”F:DivSepMar” (Female, Divorced/Separated/Married) ,”M:Single” (Male, Single), ”F:Single” (Female, Single).

#### OtherParties (F)
Other parties with an interest. Levels: ”None”,”Coapp” (another co- applicant), ”Guarantor” (a guarantor).

#### Residence (C)
Full years in current residence.

#### Property (F)
Most valuable significant asset. Levels: ”House”,”Savings”,”Car”,”None”. Age (C). Age of applicant.

#### Plans (F)
Other current loan plans. Levels: ”Bank”,”Stores”,”None”.

#### Housing (F)
Ownership status of accommodation. Levels: ”Rent”,”Own”,”RentFree”. Existing (C). Number of existing credits at this bank.

#### Job (F)
Level of current job. Levels: ”Unemployed”,”Unskilled”,”Skilled”,”Management:Self”. Dependants (C). Number of dependants.

#### Telephone (F)
Does the applicant have a registered phone in their name? Levels: ”No”,”Yes”. Foreign (F). Is the applicant a foreign worker? Levels: ”Yes”,”No”.

#### CreditScore (C)
Credit score of the applicant. Higher is better (considered less risky).
