[sample_input.json](https://github.com/user-attachments/files/25599227/sample_input.json)
{
  "market": {
    "kospi_rsi": 52.0,
    "kosdaq_rsi": 54.0
  },
  "sectors": {
    "Semiconductors": {
      "avg_change_pct": 1.2,
      "value_growth_pct": 15,
      "top_movers": 4
    },
    "Robotics": {
      "avg_change_pct": 2.1,
      "value_growth_pct": 18,
      "top_movers": 3
    },
    "Energy": {
      "avg_change_pct": 0.6,
      "value_growth_pct": 6,
      "top_movers": 2
    }
  },
  "stocks": [
    {
      "symbol": "005930",
      "name": "Samsung Electronics",
      "sector": "Semiconductors",
      "market_cap_krw": 400000000000000,
      "price": 70000,
      "change_pct": 1.8,
      "value_krw": 1800000000000,
      "value_growth_pct": 12,
      "rsi": 55,
      "bull_div": true,
      "macd_cross_up": true,
      "double_bottom_ok": true,
      "intraday_gain_pct": 4.5,
      "close_to_high_gap_pct": 1.9,
      "risk_flag": false
    },
    {
      "symbol": "277810",
      "name": "Rainbow Robotics",
      "sector": "Robotics",
      "market_cap_krw": 6500000000000,
      "price": 150000,
      "change_pct": 3.2,
      "value_krw": 120000000000,
      "value_growth_pct": 22,
      "rsi": 58,
      "bull_div": true,
      "macd_cross_up": true,
      "double_bottom_ok": true,
      "intraday_gain_pct": 6.2,
      "close_to_high_gap_pct": 1.4,
      "risk_flag": false
    }
  ]
}
