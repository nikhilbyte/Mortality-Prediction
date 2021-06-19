# Mortality-Prediction
to be or not to be ?


Please refer to the [“**CodaLab Challange**”](https://competitions.codalab.org/competitions/30715) for more details.

To obtain the dataset:
Join the Competition & then:
```wget https://competitions.codalab.org/my/datasets/download/9d49b18f-3861-44c1-8412-67fbb60dc0a3```
## Method Overview
The training dataset contains information about 80,000 patients, represented by categorical, binary and numerical features including age, gender, ethnicity, marital status, as well as medical data such as blood pressure rate or glucose rate. The following models were employed to predict if the patient died or not.
- LightGBM
- XGBClassifier
- CatBoost
Cross Validation was performed using [Optuna](https://optuna.org/).
This landed me on the 12th spot on the final [leaderboard](https://competitions.codalab.org/competitions/30715#results).


