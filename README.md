# Grocery-Bazaar-Sales-Analytics-A-2-Year-Transaction-Deep-Dive-Analysis


<img width="881" height="419" alt="Grocery_Bazaar_Dashboard" src="https://github.com/user-attachments/assets/13788ac5-65e1-4acf-a7c8-a40a1f0d5bf7" />


Introduction

This project presents an in-depth analysis of Grocery Bazaar, a regional grocery retail chain operating 10 stores across diverse locations. The dataset encompasses 1,980 customer transactions spanning nearly two years (August 2023 — August 2025), capturing the full spectrum of retail operations including sales performance, customer behavior, product dynamics, and loyalty program effectiveness.

With a total revenue of $82,037.31 across 1,798 unique customers purchasing from 18 distinct products organized in 11 aisles, this analysis provides actionable insights into grocery retail operations, customer preferences, and strategic growth opportunities.

The dataset reveals a micro-to-medium transaction retail model where the average customer spends $41.43 per visit, with most customers (1,798) making an average of just 1.10 visits during the analysis period, highlighting significant opportunities for customer retention and lifetime value optimization.


Data Story:

The Retail Landscape

Grocery Bazaar’s story unfolds across a 10-store network with striking performance disparities. The flagship GreenGrocer Plaza ($9,880.76 in sales) and SuperSave Central ($9,859.89) lead the pack, while FamilyFood Express ($7,719.49) and the mysterious Unknown Store ($1,156.18) lag significantly behind.


The Customer Journey

The typical Grocery Bazaar customer is a single-visit shopper (average 1.10 visits) who spends around $41–42 per transaction. However, the dataset reveals fascinating extremes:

Top spender: Customer #2276 spent $250.84 across just 2 visits (avg. $125/visit)

Loyalty champion: Customer #8381 made 4 visits, accumulating 1,120 loyalty points

Transaction spread: 41% of transactions fall below $25, while only 2% exceed $125


Product Power Players:

The grocery essentials dominate both sales and loyalty metrics:

Chicken Breast leads in revenue ($5,172.88) and quantity (379 units)

Onions command the highest loyalty points (33,925), despite lower revenue

Tomatoes balance both metrics with strong performance in volume (366 units) and loyalty (32,665 points)

These staples represent the backbone of repeat purchasing behavior, with customers consistently returning for these core items.


The Seasonal Pulse:

Sales demonstrate clear seasonal volatility:

Peak Performance: March 2024 ($8,204.51) — 33% above average

Low Point: June 2024 ($5,963.18) — 13% below average

Year-End Decline: December ($6,146.87) shows traditional holiday period weakness.



Objective of the Project

Primary Research Questions:

Revenue Optimization: How can Grocery Bazaar increase the average transaction value from $41.43 to $55+ through strategic interventions?

Customer Retention: What drives the low 1.10 visit-per-customer rate, and how can we improve retention by 50%?

Store Performance: Why does GreenGrocer Plaza outperform FamilyFood Express by 28%, and what practices can be replicated?

Product Strategy: Which products drive loyalty vs. revenue, and how can we optimize the portfolio for both metrics?

Seasonal Planning: What causes the 38% swing between peak (March) and trough (June) months, and how can we smooth demand?



Business Objectives:

Increase Average Transaction Value by 25% through upselling and bundling

Improve Customer Visit Frequency from 1.10 to 1.65 visits (50% increase)

Standardize Store Performance to reduce the 28% gap between top and bottom performers

Optimize Discount Strategy to reduce the 9.74% discount rate while maintaining sales volume

Enhance Loyalty Program ROI to convert loyalty points into measurable repeat purchase behavior



Methodology

Analytical Framework:

This analysis employs a multi-phase analytical approach combining descriptive, diagnostic, and prescriptive analytics:


Phase 1: Descriptive Analytics

Transaction Analysis: Volume, frequency, and value distributions

Performance Benchmarking: Store, product, and aisle-level metrics

Temporal Pattern Recognition: Monthly, quarterly, and seasonal trends

Customer Behavior Profiling: Spending patterns, visit frequencies, loyalty engagement



Phase 2: 

Diagnostic Analytics

Root Cause Analysis: Performance variance investigation

Correlation Studies: Loyalty points vs. revenue, discount impact on basket size

Segmentation Analysis: Customer value tiers, product categories, store clusters

Anomaly Detection: Outliers, returns/refunds, negative transactions



Phase 3: Prescriptive Analytics

Opportunity Quantification: Revenue gaps and improvement potential

Scenario Modeling: Impact of strategic interventions

Best Practice Identification: Replicable success patterns

Actionable Recommendations: Prioritized initiatives with ROI estimates



Tools & Techniques:

Data Processing: 

Excel for data manipulation and aggregation

Statistical Analysis: Descriptive statistics, distribution analysis, correlation matrices

Visualization: Dashboard interpretation, trend analysis, comparative charts
Business Intelligence: Pivot analysis, drill-down investigations, cross-tabulations

Domain Expertise: Retail operations knowledge, customer behavior psychology, grocery industry benchmarks


Quality Assurance:

Data Validation: Cross-referencing aggregated sheets with raw transaction data

Consistency Checks: Ensuring totals match across different analytical views

Outlier Investigation: Examining extreme values for legitimacy

Missing Value Analysis: Identifying and addressing data gaps.


Data Splitting:

1.Category One — Independent Values

Store Name

Aisle (Catogory)

Product_name


2. Category Two — Dependent Values

Quantity

Unit_price

Total_amount

Discount_amount

Final_amount

Loyalty point



POTENTIAL ANALYSIS / QUESTIONS

which stores generates the highest sales

Which aisle generates the most sales in terms of quantity and total amount

Are there any products that consistently receive high discounts

Which product categories have the highest unit prices

Does the aisle/category of a product influence the loyalty points earned by customers?

How does category influence the final amount spent by customers?

Are there any patterns in discount amounts offered by different stores or categories?

Is there a relationship between the quantity sold and revenue generated



POTENTIAL INSIGHT:

Identify which stores generate the highest sales

Determine which aisles generate the most sales in terms of quantity and total amount

Analyze which product categories have the highest unit prices and assess their impact on sales volume and revenue.

Identify products that consistently receive high discounts and evaluate their effect on profit margins and customer purchasing behavior.

Investigate whether aisle or category influences loyalty points earned by customers, and adjust loyalty programs to maximize customer engagement.

Discover patterns in discount amounts offered by different stores or categories

Analyze how category influences the final amount spent by customers.
Examine the relationship between quantity sold and revenue generated.



ANALYSIS:

Stores By Sales Generated — Bar Chart

![1_49tZn7BFfXEcIZwVZPZwgQ](https://github.com/user-attachments/assets/718fbfcf-a8ba-4942-ab5b-384a499d0c9b)


OBSERVATION:

- GreenGrocer Plaza $9,880.76 and SuperSave Central $9,859.89 are leading the pack, both generating close to $9,900 in sales clearly top performers.

- City Fresh Store $9,788.70 and MegaMart Westside $9,295.79 are in the upper-middle tier, not far behind the leaders, suggesting solid performance.

- Corner Grocery $9,285.50 is holding its own, but slightly below the top four but still respectable.

- ValuePlus Market $8,661.24, FreshMart Downtown $8,206.87 and QuickStop Market with $8,182.89 are in the lower-middle range, indicating room for improvement.

- FamilyFood Express generated the lowest sales among the identified store owners, with total sales of $7,719.49. However, this figure is significantly higher than the Unknown Store, which had sales of approximately $1,100, with a substantial difference of over $6,000.

- The Unknown Store is significantly underperforming, with total sales of approximately $1,100. However, there appears to be a potential error in the dataset, and it’s possible that these sales may be attributed to a different store with a similar name. Further investigation is necessary to verify the accuracy of the data.


PRE-INSIGHT:

- GreenGrocer Plaza and SuperSave Central are the top-performing stores, generating sales close to $9,900.

- City Fresh Store and MegaMart Westside are consistently performing well, indicating solid sales strategies.

- Corner Grocery, ValuePlus Market, FreshMart Downtown, and QuickStop Market are clustered in the middle tier, suggesting opportunities for growth and improvement.

- ValuePlus Market, FreshMart Downtown, and QuickStop Market are in the lower-middle range, indicating potential areas for improvement in sales strategies or operations.

- FamilyFood Express has the lowest sales among identified store owners, but still significantly outperforms the Unknown Store.

- The Unknown Store’s sales data appears suspiciously low, and potential errors in the dataset may be attributing sales to the wrong store.

There are noticeable gaps in sales performance between top-performing stores and those in the lower-middle range, suggesting opportunities for knowledge sharing or best practice adoption.



2. Top 5 Sales by Aisle — Pie Chart
   

![1_mt3smvV_9elcjj02FZSR4w](https://github.com/user-attachments/assets/c0cd7d34-df45-4883-9451-57783a225df8)

   

 OBSERVATION

- Personal Care is leading the pack with over $8,289 in sales clearly the aisle customers are flocking to.

- Snacks & Candy and Canned Goods are neck-and-neck, both hovering just above $8,000. That’s a tight race for second place.

- Health & Wellness and Beverages round out the top five, but they are trailing slightly behind the others.

- The sales gap between the highest and lowest aisle is under $500, which shows a relatively balanced performance across categories.

- All five aisles are pulling in over $7,800, which signals strong overall demand in these product areas.



PRE-INSIGHT

— The dominance of Personal Care suggests customers may be prioritizing hygiene and self-care possibly influenced by seasonal trends or promotions.

- The close competition between Snacks & Candy and Canned Goods could mean shoppers are stocking up on comfort and convenience foods.

- Health & Wellness might benefit from a targeted push like bundling with Personal Care or spotlighting immunity-boosting products.

- The relatively small spread in sales implies that no aisle is underperforming, but there’s still room to optimize each one.

If Beverages consistently ranks lower, it might be time to rethink the product mix or shelf placement to boost visibility and appeal.



3. Top 10 Product Sales By Quatity — Column Chart


   ![1_l70I2-Liw9mCJFW3IpydTg](https://github.com/user-attachments/assets/c9278d09-d001-4ade-93e3-31050b921d0a)



OBSERVATION

- Chicken Breast takes the lead with 131 units sold, as it is a staple food in many households.

- Onions and Tomatoes are practically tied with 127 and 126 units sold, respectively.

- Bread is narrowly in fourth place with 121 units sold, showing its importance in everyday meals.

- Potatoes at 5th place with 118 units sold.

- there is no much difference with unit sold between Egg, Salmon, and Cereal, only 1–2 units difference 113–114 units sold.

- Orange Juice is second to the last on the chart with 112 units sold.

- Yogurt is sitting at the bottom of the table with 109 units sold.



PRE-INSIGHT

- Food products that are high in protein are important to consumers, as Chicken Breast and Salmon are in the top 5.

- Onions, Tomatoes, Bread, and Potatoes are popular because they are staples in cooking and baking.

- Breakfast items, such as Cereal and Orange Juice, are currently in high demand.

- Unit sales of Egg, Salmon and Cereal have small gaps between them suggesting competition in the market space.

- Yogurt has low unit sales among food products, indicating not all dairy products are equally satisfying for consumer demand.

- The top products have unit sales that are close together, suggesting they offered a good selection of items.



4. Sales Trend By Report — Line Chart


   ![1_m_2E4EEiU039lc_qhzhC8g](https://github.com/user-attachments/assets/b0642483-6f30-4d27-8b28-2fd3fb1fe5ff)

   

OBSERVATION

- The month of March recorded the highest sales revenue generating a total sum of $8,204.51

- October came second with the sales generated to be $7,866.49

- November in close gap with October generated $7,406.05 and this place the month to third position

- May closely tailing November with total sales of $7,125.64.

- All the months (April, July, August, February, January, Septemberand December) have sales figures that are relatively close, ranging from $6,146.87 to $6,780.51, indicating a stable sales performance across these periods.

- Despite a sharp rise in Marh with sales of $8,204.51, April saw a significant decline in sales, generating $6,780.51. This substantial drop warrants attention and further analysis to identify the causes.

- June had the lowest sales performance, generating $5,963.18



PRE-INSIGHT:

- March strong sales performance needs to be studied and replicated in other months most especially June

The store owners should analyze the factors that drove March’s sales surge, such as promotions, discounts, or price reductions, and apply similar strategies to other months, including April, July, August, February, January, September, and December.

- January’s relatively better performance suggests that February’s dip may be due to specific factors rather than a straightforward post-holiday trend.



5. Transaction By Amount — Column chart
  
 ![1_8S-gSfM165vN8fsZ7_VmUw](https://github.com/user-attachments/assets/5af44cb2-885d-40f2-ab28-13300ec1e6b8)


OBSERVATION

- The majority of sales comes from lower price points with the highest count of sales 731 observed in the 0–25 price range.

- The price groups $25-$50 and $50-$75 have steady sales ranging from 344 to 487 units, ranking them second and third in the chart. This suggests consistent demand across these price groups.

There’s an inverse relationship between price and revenue count. As the price increases, the count of revenue decreases.

- The 0-$25 and $25-$50 price ranges are the top contributors to sales, accounting for 731 and 487, respectively.

- The highest price ranges $125-$150 and $100-$125 have the lowest sales counts, contributing 65 and 122, respectively.



PRE-INSIGHT

- Price Sensitivity is the majority of price generated from lower price points 0-$25, suggesting customers are highly price-sensitive

- As prices increase, sales counts decrease, indicating potential pricing strategy opportunities.

The 0-$25 and $25-$50 price ranges generate the most revenue, so optimizing these segments is key.




6. Top 6 Product By loyalty Point — Bar Chart
  
 ![1_eiwerLUT0OxE7QAUAIF89w](https://github.com/user-attachments/assets/4995f827-e573-444d-bd9e-3c2edf9fa2f6)


OBSERVATION

- Onions have 33,925 loyalty points, indicating that customers are highly engaged with this product. This could be due to factors like quality, pricing, or versatility in cooking.

- Tomatoes have 32,665 loyalty points, demonstrating strong customer loyalty. This might be attributed to the product’s freshness, taste, or nutritional value.

- Cereal and bread also show significant loyalty points, although lower than the top two. Cereal has 31,129 loyalty points.

- Bread has 31,091 loyalty points, possibly due to its staple nature, quality, or variety.

- Chicken breast and potatoes are also among the top products, indicating that customers value protein-rich and staple products.



PRE-INSIGHT

- Customers like products that are important, useful, and of good quality.

- Things like quality, price, taste, and nutrition make customers loyal to certain products.

- Customers value basic products like bread and onions, and healthy products like chicken.

Customers stick to products that meet their needs and are good for them.


Post-Analysis Observations

1. Transaction Amount Distribution
Majority of transactions fall within the 0–50 range, indicating customers are making smaller purchases.
Very few transactions exceed $100, suggesting limited high-value shopping behavior.

2. Sales by Aisle
Snacks & Candy ($8,289.12) and Canned Goods ($8,066.95) lead sales, showing strong demand for convenience and indulgence items.
Personal Care and Health & Wellness aisles also perform well, reflecting consumer interest in lifestyle and wellness products.

3. Product Sales (Quantity)
Chicken, onions, tomatoes, bread, and potatoes dominate in volume, highlighting staple food items as consistent drivers of sales.
Repetition of onions in the top 10 suggests possible data duplication or strong recurring demand.

4. Loyalty Products
Onions, tomatoes, cereal, bread, chicken breast, and potatoes show the highest loyalty scores, meaning customers repeatedly purchase these items.
Loyalty is concentrated around basic staples, reinforcing their importance in customer retention.

5. Store Performance
GreenGrocer Plaza and SuperSave Central are top performers, each generating nearly $9,900 in sales.
Unknown Store contributes very little ($1,156.18), which may indicate incomplete data capture or underperformance.

6. Sales Trend (Monthly)
March ($8,204.51) and October ($7,866.49) are peak months, possibly tied to seasonal promotions or holidays.
June ($5,963.18) and December ($6,146.87) are the weakest months, suggesting seasonal dips or missed opportunities.


Recommendations

1. Transaction Growth
Introduce bundle deals or loyalty discounts to encourage customers to increase basket size beyond $50.
Promote premium products to shift some transactions into higher-value ranges.

2. Aisle Strategy
Expand Snacks & Candy and Canned Goods offerings, as they are strong revenue drivers.
Cross-promote Health & Wellness with Personal Care to capture lifestyle-focused customers.

3. Product Optimization
Ensure staple items (onions, tomatoes, bread, chicken, potatoes) are always in stock to maintain loyalty.
Investigate the duplicate onion entry in product sales to refine reporting accuracy.

4. Store-Level Actions
Analyze why Unknown Store has low sales — check for data entry issues or operational inefficiencies.
Replicate successful strategies from GreenGrocer Plaza and SuperSave Central across lower-performing stores.

5. Seasonal Promotions
Boost marketing and promotions in June and December to counteract sales dips (e.g., summer campaigns, holiday bundles).
Leverage March and October peaks by planning major promotions during these months to maximize momentum.

6. Customer Loyalty Programs
Strengthen loyalty programs around staple products, offering points or discounts for repeat purchases.
Introduce personalized offers based on customer purchase history to deepen engagement.



Conclusion Note

The dataset from the grocery bazaar sales provides valuable insights into customer purchasing behavior, product performance, and store-level sales trends. The analysis reveals that transactions are predominantly low-value, with staple items such as onions, tomatoes, bread, chicken, and potatoes driving both volume and loyalty.

Aisle-level sales highlight strong demand for snacks, canned goods, and wellness-related products, while store performance shows significant variation, with top outlets consistently outperforming weaker ones.

Seasonal fluctuations in monthly sales further emphasize the importance of targeted campaigns to sustain revenue during off-peak periods.

Overall, the dataset underscores the need for a balanced strategy that focuses on increasing basket size, ensuring product availability, optimizing underperforming stores, and leveraging seasonal promotions. By acting on these insights, the business can strengthen customer loyalty, enhance operational efficiency, and achieve sustainable growth across all dimensions of performance.
   

   
