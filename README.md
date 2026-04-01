# Indian-E-Commerce-Analysis
This project provides a comprehensive analysis of the Indian E-commerce landscape, focusing on the relationship between pricing strategies, discount tiers, and regional revenue performance. Using a dataset of ~30,600 transactions, I developed an interactive Power BI/Excel dashboard to help stakeholders optimize discounting and inventory management.
🛠️ Tech Stack & Workflow
Data Cleaning: Power Query (ETL) – used for handling nulls, normalizing dates, and creating custom conditional columns.

Analysis: Excel Pivot Tables & Power Pivot (DAX).

Visualization: Interactive Dashboard with Slicers, KPI Cards, and Dynamic Charts.

🧼 Data Transformation (Cleaning)
Before analysis, the following steps were taken in Power Query:

Discount Categorization: Created a conditional column to group discounts into tiers:

Low (0-15%)

Medium (16-35%)

High (36-45%)

Ultra (46-65%)

Demographic Segmentation: Grouped customer_age into brackets (18-25, 26-35, 36-45, 46-65) to identify high-value age groups.

Data Validation: Verified zero duplicate records and ensured 100% data integrity for pricing and revenue columns.

📈 Key Findings & Insights
1. The Revenue Engine
Total Market Scale: The platform generated ₹2.17 Billion in total revenue with ~970,188 units sold.

Dominant Category: Premium Lifestyle emerged as the primary revenue driver across all age demographics, contributing significantly to the high Average Order Value (AOV) of ₹71,062.

2. Discount Sensitivity (The "Flash Sale" Effect)
Volume Explosion: Units sold per order jump from an average of 17 (Low Discount) to 41 (Ultra Discount).

Inventory Link: High discounts (43.2% avg) are strongly correlated with High Inventory Pressure, proving that the platform effectively uses pricing to clear stock.

3. Regional Performance
South Zone Leadership: The South Zone leads in total volume, but Delhi NCR and Karnataka are the most profitable regions, boasting AOVs above ₹87,000.

Competition Impact: In regions with "High" competition intensity, final prices dropped by 15%, but sales volume increased by 14%, suggesting a highly price-sensitive consumer base.

4. Sales Event Impact
Festival Power: During festival events, average discounts hit 44.8%, driving massive volume.

Sustainability: Despite the peaks during festivals, "Normal" sales days still contribute 65% of total revenue, indicating a stable, non-reliant business model.

📊 Dashboard Preview
The final dashboard includes:

KPI Cards: Real-time tracking of Revenue, AOV, Avg Discount, and Units Sold.

Regional Bar Chart: Breakdown of revenue by Zone and State.

Sensitivity Heatmap: Comparison of product category performance across different discount tiers.

Interactive Slicers: Filters for Zone, Category, Brand Type, and Sales Event.

💡 Strategic Recommendations
Optimize "Medium" Tiers: Shift focus to the 25-35% discount tier for "Normal" days to maintain volume without heavy margin erosion.

Targeted Premium Marketing: Increase marketing spend in Delhi NCR and Karnataka for "Premium Lifestyle" products, as these regions show the highest willingness to spend.

Inventory Clearing: Continue using "Ultra" discounts (50%+) exclusively for high-inventory pressure items to maintain logistics flow.
