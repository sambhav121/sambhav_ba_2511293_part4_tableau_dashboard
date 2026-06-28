# Sales Dashboard Analysis

## KPI Summary

| metric | value |
| --- | --- |
| Orders | 4200.0000 |
| Total sales | 217017651.9200 |
| Total profit | 33306312.8400 |
| Profit margin | 0.1535 |
| Quantity sold | 23112.0000 |
| Return rate | 0.0455 |
| Average delivery days | 3.5929 |
| Average customer rating | 4.0631 |
| Missing customer ratings | 32.0000 |
| Missing campaign channels | 24.0000 |

## Region Performance

| region | orders | sales | profit | quantity | returns | avg_delivery_days | avg_rating | profit_margin | return_rate |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| South | 1210 | 64,693,706.73 | 9,987,912.33 | 6712 | 55 | 3.4380 | 4.0612 | 15.44% | 4.55% |
| North | 1056 | 54,555,800.53 | 8,314,884.01 | 5718 | 47 | 3.3712 | 4.0716 | 15.24% | 4.45% |
| West | 1037 | 48,908,980.24 | 7,404,073.37 | 5747 | 45 | 3.4060 | 4.0749 | 15.14% | 4.34% |
| East | 897 | 48,859,164.42 | 7,599,443.13 | 4935 | 44 | 4.2787 | 4.0420 | 15.55% | 4.91% |

## Category Performance

| category | orders | sales | profit | quantity | returns | avg_delivery_days | avg_rating | profit_margin | return_rate |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Technology | 1384 | 153,895,267.89 | 28,043,309.91 | 7522 | 42 | 3.5434 | 4.0823 | 18.22% | 3.03% |
| Furniture | 1147 | 51,641,015.61 | 3,557,835.43 | 6422 | 88 | 3.6888 | 4.0278 | 6.89% | 7.67% |
| Office Supplies | 1669 | 11,481,368.42 | 1,705,167.50 | 9168 | 61 | 3.5680 | 4.0713 | 14.85% | 3.65% |

## Findings

- Total sales are 217,017,651.92 and total profit is 33,306,312.84, for an overall profit margin of 15.35%.
- South is the highest-sales region with 64,693,706.73 in sales and 9,987,912.33 in profit.
- Technology is the highest-sales category with 153,895,267.89 in sales.
- The weakest sub-category by profit is Paper in Office Supplies, with profit 318,706.90.

## Recommendations

- Prioritize inventory and campaign support for the highest-profit regions and categories shown in `sales_dashboard.xlsx`.
- Investigate low-profit sub-categories before increasing discounting, since profit margin differs substantially by category and sub-category.
- Monitor returns by ship mode and campaign channel because return rates directly reduce realized profitability.

## Data Limitations

- `customer_rating` has 32 missing rows.
- `campaign_channel` has 24 missing rows.
