Life-Cycle Portfolio Optimization (Python)

Overview

This project implements a life-cycle retirement portfolio optimization framework for a long-term investor with a 15-year horizon. Instead of a static asset allocation, the portfolio follows a dynamic glide path, gradually reducing risk as the investor approaches retirement. The focus is on constraint-based portfolio optimization, realistic rebalancing, and risk analysis rather than unconstrained one-period mean–variance optimization.

Key Features

• Life-cycle glide path: Equity exposure decreases from 70% to 40% over 15 years

• Constraint-based solver optimization reflecting realistic portfolio limits

• Annual contributions and rebalancing to maintain target risk levels

• Scenario analysis (base, optimistic, pessimistic) to assess downside risk near retirement

• Risk evaluation using Volatility, Beta, Sharpe Ratio, and Capital Allocation Line (CAL)

Methodology

• Market data is processed using Python (pandas)

• Asset returns and the covariance matrix are estimated from historical price data

• Portfolio weights are optimized using a solver under predefined constraints

• The optimization is repeated annually to reflect the evolving glide path

• Portfolio risk and performance metrics are tracked across the investment horizon

Risk Metrics Used

• Expected Return

• Volatility (Standard Deviation)

• Beta (Market Risk)

• Sharpe Ratio

• Capital Allocation Line (CAL)

Why This Approach?

Traditional portfolio optimization assumes a single-period decision.

This project instead treats portfolio construction as a dynamic, multi-period problem, where risk tolerance and recovery capacity change over time.

The goal is not to maximize return at every point, but to balance growth early on with capital preservation closer to retirement.

Technologies

• Python

• pandas

• Solver-based optimization

• Excel (for validation and reporting)

Use Cases

• Retirement portfolio design

• Life-cycle asset allocation analysis

• Risk-aware portfolio optimization

Disclaimer

This project is for educational purposes only and does not constitute investment advice.



