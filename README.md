# BTC-LCA
# Description

Köhler S and Pizzol M, Life Cycle Assessment of Bitcoin Mining, (under review), doi to be added.

The supplementary materials to the article include the raw data:

inventory tables: 
Attributional_model.csv, Attributional-10percent_electricity.csv, Attributional+10percent_electricity.csv, Attributional-10percent_hashrate.csv, Attributional+10percent_hashrate.csv, Attributional_Lifetime1.csv, Attributional_Lifetime2.csv, Attributional_Location_Bendiksen_et_al.csv, Attributional_Location_Rauchs_et_al.csv, Attributional_Location_Mining_Pools.csv, Attributional_Location_Coal.csv, Attributional_Location_Global.csv, Attributional_Location_Hydro.csv, Consequential_Scenario1.csv, Consequential_Scenario2.csv, and Consequential_Scenario3.csv

These are needed to run the scripts contained in this repository, for example if you want to reproduce the results of the paper. If you don't have access to the article or the files, you can get them from me directly, please send a request to susanne@plan.aau.dk

# The repository includes

BTC_Att_LCA.ipynb and BTC_Consequential_LCA.ipynb Python script to reproduce results of the LCA using the brightway2 LCA software. Imports the inventory in, performs LCA calculations and exports LCIA results, runs comparative Monte Carlo for the global warming impact category and exports results.

lci_to_bw2.py A little python script to import inventory tables in .csv directly into brightway2.

Please get in touch if you find any mistake or problem in running these scripts.

# DOI and versions

