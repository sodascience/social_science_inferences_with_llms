# Addressing LLM-related Measurement Error in Social Science Modeling Research

With the advent of large language models (LLMs), the collection of measurements related to  <ins>social science constructs</ins> (e.g., personality traits, political attitudes, human values) has become easier, faster and more affordable. These measurements are subsequently used for <ins>modelling of societal and group processes</ins> that social scientists typically engage in, where <ins>inferences from samples to populations are also made</ins>. Valid modelling and inferences, however, requires high-quality measurements or at the very least, <ins>methods to deal with the presence of measurement error</ins>. Just like traditional questionnaire-based measurements, LLM-based measurements have been shown to suffer from validity and reliability issues. 

While there is an abundance of research literature in dealing with measurement error, they focus on questionnaire-based measurement error. <ins>It is unclear yet how measurement issues arising from LLMs should be handled in social science modelling research</ins>. 

This study has two primary objectives. First, we <ins>review existing literature</ins> to identify practices for addressing LLM-related measurement error, both in computer science and in social sciences. Second, we synthesise these findings with existing measurement modelling literature to propose <ins>a practical framework</ins> for making valid inferences using LLM-based measurements in social sciences. By bridging the gap between LLM prediction capabilities and social science inference requirements, our framework aims to enhance the reliability and validity of social science research outcomes in the era of LLMs.

## Literature Overview
### Inferences with LLMs

| Year | Title | Predicted Variable(s) | 
| --- | --- | --- |
| 2023 | [Using Imperfect Surrogates for Downstream Inference: Design-based Supervised Learning for Social Science Applications of Large Language Models](https://openreview.net/pdf?id=e8RZwixcE4) | Outcome |
| 2024 | [Using Large Language Model Annotations for the Social Sciences: A General Framework of Using Predicted Variables in Downstream Analyses](https://naokiegami.com/paper/dsl_ss.pdf) | Predictor and outcome |

### Inferences with Machine Learning Predictions

| Year | Title | Predicted Variable(s) | 
| --- | --- | --- |
| 2020 | [Methods for correcting inference based on outcomes predicted by machine learning](https://www.pnas.org/doi/full/10.1073/pnas.2001238117?gad_source=1&gclid=CjwKCAiAxqC6BhBcEiwAlXp45xykgurcH-QuopXIjbAOtssXUZoCauzjRRTmmd-Ud3FFmJp3RhODIBoCgUsQAvD_BwE) | Outcome |
| 2022 | [How Using Machine Learning Classification as a Variable in Regression Leads to Attenuation Bias and What to Do about It](https://ideas.repec.org/p/osf/socarx/453jk.html) | Predictor or outcome |
| 2023 | [Prediction-powered inference](https://www.science.org/doi/10.1126/science.adi6000) | Outcome |
| 2024 | [PPI++: Efficient Prediction-Powered Inference](https://arxiv.org/abs/2311.01453) | Outcome |
| 2024 | [Cross-prediction-powered inference](https://www.pnas.org/doi/abs/10.1073/pnas.2322083121?gad_source=1&gclid=CjwKCAiAxqC6BhBcEiwAlXp455jkwwIzsaI_14eWknuE5daWeUS4TGu8V--VwXJf9bGEUJ5vJodv7BoCEGEQAvD_BwE) | Outcome |
| 2024 | [A Note on the Prediction-Powered Bootstrap](https://arxiv.org/abs/2405.18379) | Outcome |
| 2024 | [Assumption-Lean and Data-Adaptive Post-Prediction Inference](https://arxiv.org/abs/2311.14220) | Predictor and outcome |
| 2024 | [ipd: An R Package for Conducting Inference on Predicted Data](https://arxiv.org/abs/2410.09665) | Outcome |
| 2024 | [Task-Agnostic Machine-Learning-Assisted Inference](https://arxiv.org/abs/2405.20039) | Outcome |
| 2024 | [Prediction De-Correlated Inference: A safe approach for post-prediction inference](https://arxiv.org/abs/2312.06478) | Outcome |

### Inferences with Measurement Error
| Year | Title | 
| --- | --- |
| 2023 | [Using Imperfect Surrogates for Downstream Inference: Design-based Supervised Learning for Social Science Applications of Large Language Models](https://openreview.net/pdf?id=e8RZwixcE4)
| 2024 | [Using Large Language Model Annotations for the Social Sciences: A General Framework of Using Predicted Variables in Downstream Analyses](https://naokiegami.com/paper/dsl_ss.pdf)

### Other Approaches
e.g., Missing data imputation, semi-supervised learning, conformal prediction. 
TBA.

## A Guiding Framework

## Datasets

## Contact
<img src="./img/soda_logo.png" alt="SoDa logo" width="250px"/>

This project is developed and maintained by the [ODISSEI Social Data
Science (SoDa)](https://odissei-soda.nl) team.

Do you have questions, suggestions, or remarks? File an issue in the
issue tracker or feel free to contact the team at [`odissei-soda.nl`](https://odissei-soda.nl)
