# Uniswap (Ethereum) Activity - 30D

## Dashboard
- Dune: https://dune.com/siyi/uniswap-ethereum-activity-30d

## Metrics
- Daily Volume (USD): ROUND(SUM(amount_usd), 2)
- Daily Transactions: COUNT(DISTINCT tx_hash)
- Daily Unique Traders (est.): COUNT(DISTINCT COALESCE(taker, maker))

## Data source & notes
- Source: Dune curated table `dex.trades`
- Note: Unique traders is an estimate based on taker/maker fields and may differ from end-user identity attribution.

