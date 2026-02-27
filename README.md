# Trader Behavior vs Market Sentiment Analysis

## Objective
Analyze how Bitcoin market sentiment (Fear/Greed) influences trader behavior and performance on Hyperliquid.

## Dataset
- Bitcoin Fear/Greed Sentiment
- Hyperliquid Historical Trader Data

## Methodology
- Cleaned and aligned sentiment and trader datasets by date
- Computed daily trader metrics: PnL, win rate, leverage, trade size, trade frequency, long/short ratio
- Compared metrics across sentiment regimes (Fear vs Greed)
- Visualized behavior and performance patterns
- Derived sentiment-aware trading strategies

## Key Insights
- Trader performance deteriorates during Extreme Fear regimes
- Traders use higher leverage during Greed markets
- Trade frequency increases during Fear periods
- Directional bias remains relatively stable across sentiment

## Strategy Recommendations
- Reduce leverage during Fear markets
- Increase trading activity during Fear volatility
- Apply higher leverage selectively during Greed regimes

## Bonus
- Trader clustering into behavioral archetypes
- Profitability prediction using RandomForest

## How to Run
1. Open notebook in Jupyter or Colab
2. Install requirements:
   pip install pandas numpy matplotlib seaborn scikit-learn
3. Run all cells sequentially

## Output
Charts and metrics showing sentiment-driven trading behavior patterns.
