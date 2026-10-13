# Lab-5-Probability-Simulation
Econ lab 5
# Monte Carlo Engine -- Probability & Simulation

## Objective
I used Monte Carlo simulation in Python to estimate probabilities and financial risk by drawing many random cases and counting the results.

## Methodology
- Simulated 10,000 fair coin flips and plotted the running share of heads to see the Law of Large Numbers in action.
- Simulated 10,000 Monty Hall games and compared the win rates for always staying and always switching.
- Applied Bayes' Theorem to a disease screening test (1% prevalence, 95% sensitivity, 90% specificity), then simulated 100,000 people to check the formula.
- Simulated 10,000 daily portfolio returns from a Normal distribution and computed the 95% and 99% Value at Risk and Expected Shortfall for a $1,000,000 portfolio.
- Estimated pi at several sample sizes and checked that the Monte Carlo error shrinks like 1/sqrt(n).

## Key Findings
- The share of heads settled close to 0.5 as the number of flips grew.
- Switching won 6,694 of 10,000 Monty Hall games, compared with 3,306 for staying.
- Only 9.2% of positive tests came from people who were actually sick, because the disease is rare and most positives were false alarms.
- The 95% VaR was $19,494: on 95% of days, the loss was smaller than that. The 95% ES was $24,230, the average loss on the worst 5% of days.
- 
