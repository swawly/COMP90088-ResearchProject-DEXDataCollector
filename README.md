# COMP90088-ResearchProject-DEXDataCollector

## Authors:

Oliver Ceff, 542138 , oceff@student.unimelb.edu.au

Akhil Nair, 1162137 , akhilsasidha@student.unimelb.edu.au

Rishabh Saxena, 1164537, rssax@student.unimelb.edu.au

---

This repo has some notebooks that fetch and display data on decentralized exchanges:

For each notebook there exists a toggle boolean at the top of the file, LOAD_FROM_FILE. Leave this boolean set to True to load pre-existing data that has been fetched from prior GraphQL queries. Setting it to False (and fetching new queries) requires providing an API key for Bitquery in a yaml file.

- 1_bitquery_eth.ipynb - fetches 3 queries and displays data on DEX platforms on ETH chain: market-cap, unique traders and trading pairs
- 2_avg_transaction_cost.ipynb - average transaction cost on ETH chain
- 3_dex_trades.ipynb - fetches data on the trade count on DEX platforms on the ETH chain