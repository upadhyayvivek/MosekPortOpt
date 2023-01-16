# MOSEK Portfolio Optimization Cookbook

The [MOSEK Portfolio Optimization Cookbook](https://docs.mosek.com/portfolio-cookbook/index.html) book provides an introduction to the topic of portfolio optimization and discusses several branches of practical interest from this broad subject. You can read it here:

* [HTML](https://docs.mosek.com/portfolio-cookbook/index.html)
* [PDF (A4)](https://docs.mosek.com/MOSEKPortfolioCookbook-a4paper.pdf), [PDF (letter)](https://docs.mosek.com/MOSEKPortfolioCookbook-letter.pdf)

It is illustrated with complete code examples using MOSEK which can be found in this repository.

# Python notebooks

Notebook | Type | Keywords | Links
--- | --- | --- | ---
[Mean-variance optimization](./python/notebooks/./ch2_mean-variance_optimization.ipynb) | CQO | Markowitz, efficient frontier, conic model, risk, return | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch2_mean-variance_optimization.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/markowitz.html)
[Preparing input data](./python/notebooks/./ch3_data_preparation.ipynb) | data transformation | distribution estimation, projection to investment horizon | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch3_data_preparation.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/inputdata.html#modeling-the-distribution-of-returns)
[Long-short dollar neutral optimization](./python/notebooks/./ch3_neutral_long-short_optimization.ipynb) | CQO | long-short, dollar neutral, gross exposure | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch3_neutral_long-short_optimization.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/inputdata.html#long-short-portfolios)
[Long-short dollar neutral optimization (fixed gross exposure)](./python/notebooks/./ch3_neutral_long-short_optimization_gross_exp_fixed.ipynb) | CQO, mixed-int | long-short, dollar neutral, gross exposure | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch3_neutral_long-short_optimization_gross_exp_fixed.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/inputdata.html#long-short-portfolios)
[Shrinkage](./python/notebooks/./ch4_shrinkage.ipynb) | CQO | shrinkage, Ledoit-Wolf, James-Stein | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch4_shrinkage.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/estimationerror.html)
[Single factor model](./python/notebooks/./ch5_factor_model_small.ipynb) | CQO | factor model | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch5_factor_model_small.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/factormodels.html)
[Large scale factor model](./python/notebooks/./ch5_factor_model_large.ipynb) | CQO | factor model | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch5_factor_model_large.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/factormodels.html)
[Market impact costs](./python/notebooks/./ch6_market_impact.ipynb) | CQO, POW | market impact, power law | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch6_market_impact.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/transaction.html#market-impact-costs)
[Transaction costs](./python/notebooks/./ch6_transaction_cost.ipynb) | CQO, mixed-int | leverage, buy-in threshold, fixed costs | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch6_transaction_cost.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/transaction.html#transaction-cost-models)
[Benchmark relative optimization](./python/notebooks/./ch7_benchmark_relative_mvo.ipynb) | CQO | active return, error tracking | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch7_benchmark_relative_mvo.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/benchmarkrel.html)
[CVaR optimization](./python/notebooks/./ch8_cvar_risk_measure.ipynb) | LO | CVaR, Monte Carlo scenarios | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch8_cvar_risk_measure.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/riskmeasures.html#conditional-value-at-risk)
[EVaR optimization](./python/notebooks/./ch8_evar_risk_measure.ipynb) | EXP | EVaR, Monte Carlo scenarios | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch8_evar_risk_measure.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/riskmeasures.html#entropic-value-at-risk)
[Expected utility maximization](./python/notebooks/./ch8_expected_utility_maximization.ipynb) | CQO, EXP | Expected utility, Gaussian mixture return | [CoLab](https://colab.research.google.com/github/MOSEK/PortfolioOptimization/blob/master/python/notebooks-colab/./ch8_expected_utility_maximization.ipynb), [Cookbook](https://docs.mosek.com/portfolio-cookbook/riskmeasures.html#expected-utility-maximization)

With a Google account you can launch the notebook directly in Google CoLab by following the CoLab link.
