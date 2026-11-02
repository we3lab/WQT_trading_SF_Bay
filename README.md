# WQT_trading_SF_Bay
A simulation model to calculate credit prices and total regional infrastructure costs for Lower South SF Bay under different market terms and market structures.

The directory contains all results and jupyter notebooks used to produce figures for this manuscript. The results are organized as follows:
1. Sensitivity_maxCredit_centralized_market_1.0: Each subfolder (either 0.1, 0.25, 0.5 or 300), contains the infrastructure planning schedule for a centralized market with a trading ratio of 1:1 and a maximum credit purchase capacity of 10%, 25%, 50% or no limit respectively.
2. Sensitivity_maxCredit_bilat_contract_1.0: Each subfolder (either 0.1, 0.25, 0.5 or 300), contains the infrastructure planning schedule for a bilateral contract with a trading ratio of 1:1 and a maximum credit purchase capacity of 10%, 25%, 50% or no limit respectively.
3. Sensitvity_bilat_partners: Infrastructure planning schedule for all combinations of bilateral contract between each WWTP pairs.
4. Exchange_market_xmax_lim: Results for a centralized market where each WWTP can only build the same maximum capacity (xmax) as their no-market maximum capacity.
5. Sensitivity_bilat_contract_yr: Results for a bilateral contract for varying number of contract years (1, 2, 5, 10, 15, and 30 years).

The notebooks will import data from the Results directory and produce the required figures. All figures will be saved in the 'Figures' or 'Figures/SI' directory.

For questions, suggestions, or issues, please contact Sinan Abi Farraj (sinanaf@stanford.edu).
