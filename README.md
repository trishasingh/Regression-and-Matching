Regression and Matching for Causal Inference
================

This is the GitHub repository for "Causal Teamwork: Regression and Matching as Supplements in the Estimation of Causal Effects" by Trisha Singh and Albert Y. Kim.

**Abstract**: The estimation of causal effects is guided by the potential outcomes framework. Regression
analysis is often used to estimate causal effects from observational data, and matching
methods are also gaining prominence. However, both methods are likely to produce biased
and inconsistent estimators due to the violation of strong assumptions associated with
approximating the potential outcomes framework using observational data. It is possible to
use regression and matching methodologies in conjunction in order to make the estimation
“doubly robust”. This paper examines estimation of causal effects using propensity score
matching methods as a supplement to regression. The paper reviews regression and matching
methods in a potential outcomes framework. We then conduct two simulation studies that
assess the performance of regression and matching methods as supplements in terms of
reducing bias. Both simulation studies indicate that: 

1.  Regression alone performs best when one of the covariates is unobserved.
2.  Regression with inverse propensity score weighting performs best by a margin when all covariates are observed.
3.  Regression on a sample balanced by matching produces low bias when one or all covariates are observed.

The paper is available [here](./regression-and-matching-paper.pdf).