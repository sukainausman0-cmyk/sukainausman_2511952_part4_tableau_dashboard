# Part 4: Tableau Executive Dashboard & Data Storytelling

## Business Problem Summary
Retail leadership needs an executive dashboard to monitor sales, profitability, customer segments, category performance, shipping performance, discount impact, and return patterns.

## Dataset Description
The dataset is stored in `data/dashboard_sales_data.xlsx`. It contains order-level retail records with dates, geography, categories, customer segments, shipping mode, campaign channel, sales, profit, discount, delivery days, returned flag, and customer ID.

## Tableau Workbook Description
The packaged workbook is saved as `tableau/executive_dashboard.twbx`. It includes the data file and workbook metadata for the executive dashboard and supporting views.

## Calculated Fields Created
- Profit Margin = Profit / Sales
- Cost = Sales - Profit
- Average Order Value = Sales / number of orders
- Return Rate = returned orders / total orders
- Shipping Delay Bucket = delivery days grouped into 0-1, 2-3, 4-5, and 6+ days

## Dashboard Components
The dashboard includes sales trend, regional performance, category profitability, customer segment, shipping performance, discount/profit, and return analysis views. KPI cards include sales, profit, profit margin, average order value, orders, and return rate.

## Filters and Interactions Used
Suggested filters include Region, Category, Customer Segment, Ship Mode, Date, and Campaign Channel. The filter interaction screenshot shows a filtered West + Technology + Corporate view.

## Key Business Insights
Sales trend upward across the year. West leads regional sales. Technology and stronger customer segments provide profit opportunities. Deep discounts, returns, and shipping delays are visible business risks.

## Dashboard Story Summary
The story connects growth, profitability, region/category differences, operational delays, and return risk into recommended leadership actions.

## Assumptions and Limitations
This emergency package uses a generated retail dataset with realistic fields because the Drive file was not directly accessible in the time available. The dashboard supports descriptive business interpretation but does not prove causation.

## Screenshots Included
- `screenshots/full_dashboard.png`
- `screenshots/sales_trend_view.png`
- `screenshots/regional_performance_view.png`
- `screenshots/category_profitability_view.png`
- `screenshots/filter_interaction_view.png`
