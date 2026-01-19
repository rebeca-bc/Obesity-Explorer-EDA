# Obesity Patterns in LATAM: An Exploratory Data Analysis (EDA) 
In this repo I wanted to explore the basic obesity levels across Latin America (specifically Colombia, Peru, and Mexico) to see if we can find any interesting patterns behind the numbers. The data comes from a study by researchers at the Universidad de la Costa (Colombia), originally sourced from the UCI Machine Learning Repository. I’m working with a simplified version (Obesidad.csv) to keep things focused and clean.

---
## 🧐 The data?
We’ve got a mix of "who you are" and "what you do":

* Sex (`Sexo`): type object. It's the gender of the individual, described as Female or Male.
* Age (`Edad`): type float64. Participant age ranging from 14 to 61 years.
* Height (`Estatura`): type float64. Height recorded in meters.
* Weight (`Peso`): type float64. Described like a number in kilograms, with decimal.
* Overweight Family History (`FamiliarConSobrepeso`): type object. Family history of overweight (yes/no).
* Caloric Intake (`ComeMuchasCalorias`): type object. Frequent intake of high-calorie foods (yes/no).
* Vegetable Intake (`ComeVegetales`): type float64. Frequency of veggie intake: (1) Never, (2) Sometimes, (3) Always.
* Smoker (`Fumador`): type object. Active smoking status (yes/no).
* Water Consumption (`ConsumoDeAgua`): type float64. Daily water intake: (1) <1L, (2) 1–2L, (3) >2L.
* Obesity Level (`NivelDeObesidad` ): type object. Weight classification based on BMI from underweight to overwight (obesity types I, II and III).

## 🛠️ The Tech Part
Observations: 2,111 individuals.
Integrity: 0 missing values (yep, the data is perfectly clean!).
Tools: Python (`Pandas`, `Matplotlib`, `Numpy`... for now).

## Project Files:
- [EDAObesityEDAReport.ipynb](./ObesityEDAReport.ipynb): The full analysis and code.
- [ObesityEDAReport.html](./ObesityEDAReport.html): A quick-look version of the results.
- [Obesity.csv](./Obesity.csv): The raw data.

## 🌙 Extra Commentary 
I even looked into a Nature study (2025) that talks about how sleep deprivation (among other things like cronic stress...) messes with your "hunger hormones" (ghrelin and leptin). It’s fascinating because it suggests that some people might eat high-calorie foods simply because they are exhausted, not just by choice. If you wanna take a look i will link it for you! 
* https://www.nature.com/articles/s41366-025-01787-5
