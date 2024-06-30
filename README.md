### Diabetes-Health-Indicators

**Author - Viswanathan Jayaraman**
#### Executive summary
Classification project for the diagnosis of diabetes based on 35 features from statistics and lifestyle survey information about people.

#### Rationale
Why should anyone care about this question?

Diabetes, a significant component of metabolic syndrome, is predominantly influenced by lifestyle choices. Current approaches primarily concentrate on managing the condition rather than aiming to reverse it. However, there exist several well-known and straightforward factors that can be focused on not only to manage but also potentially reverse the condition. 

#### Research Question
What are you trying to answer?

The dataset I'm using includes various individual factors that can notably influence the prevalence of metabolic syndrome, including diabetes. My goal is to analyze both these individual factors and their combinations to identify which ones play a significant role in the development of diabetes.

#### Data Sources
What data will you use to answer you question?

The dataset has been sourced from https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators

#### Methodology
What methods are you using to answer the question?

I began the exploratory data analysis (EDA) by plotting relevant features individually and in combinations against the target variable to assess their predictive power for diabetes. This process led to removing features that showed either zero variance or minimal significance. The remaining features were then used to establish baseline metrics, after which I employed various classification algorithms and optimization techniques to enhance the model. Ultimately, this approach helped identify the most influential features that significantly contribute to predicting diabetes.

#### Results
What did your research find?

Maintaining a healthy BMI and overall good health are crucial factors associated with the absence of diabetes. While individual factors such as high blood pressure and high cholesterol, as well as combinations thereof, can contribute to this condition, their significance is limited. Nevertheless, each of these factors does play a role to some degree.

#### Next steps
What suggestions do you have for next steps?

I want to experiment with additional classification techniques, provided my machine can handle them successfully, and aim to further enhance the metrics.

#### Outline of project
https://github.com/vizjay/Capstone---Diabetes-Health-Indicators
