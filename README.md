# Amazon Marketplace Product Performance Analysis

## Overview

This project analyses Amazon product listing and customer review data to understand differences in product performance, pricing, customer engagement and potential revenue across product categories.

The analysis was carried out in Microsoft Excel using PivotTables, calculated fields, calculated columns, charts and interactive slicers.

The main focus was on four areas:

* Product performance
* Pricing and discounts
* Customer reviews and ratings
* Revenue potential

Rather than looking at sales alone, I used product reviews, ratings, pricing and discounts to understand how different product characteristics relate to performance.

---

## Business Problem

The business wanted to understand the patterns behind product performance and identify areas that could support better decisions around pricing, promotions, inventory and customer engagement.

The analysis was designed to answer questions such as:

* Which product categories have the strongest revenue potential?
* How heavily are products being discounted?
* Which products receive the most customer engagement?
* Are high discounts associated with better product performance?
* How do ratings and review volumes vary across products?
* Which products and categories deserve closer attention?

---

## Data

The dataset contains information on Amazon product listings and customer reviews, including:

* Product category
* Product price
* Discounted price
* Discount percentage
* Product rating
* Number of reviews
* Product information
* Revenue potential

A calculated revenue-potential measure was used based on:

**Actual Price × Rating Count**

This was used as an analytical measure to compare potential revenue across categories.

---

## Tools Used

**Microsoft Excel**

* Data Cleaning
* PivotTables
* Pivot Charts
* Calculated Columns
* Calculated Fields
* Dynamic Slicers
* Dashboard Design

---

# Analysis

## 1. Product Category Performance

One of the clearest differences in the data was the level of revenue potential across product categories.

### Finding

**Electronics recorded more than ₹87M in potential revenue**, placing it significantly ahead of the other categories analysed.

This makes Electronics the strongest category in the dataset when potential revenue is measured using the project's revenue-potential calculation.

### Recommendation

Electronics should receive closer attention when reviewing inventory, advertising and promotional investment.

However, potential revenue should not be treated as actual realised revenue. The measure is based on the dataset's actual price and review count, so further sales data would be required to determine realised revenue and profitability.

---

# 2. Discounts and Product Performance

The analysis examined discount percentages across categories and compared discount levels with other measures of product performance.

### Finding

Some products with relatively heavy discounts were still performing poorly.

This suggests that a larger discount does not automatically correspond with stronger product performance.

### Recommendation

Instead of relying on discounts alone, underperforming products should be reviewed alongside:

* Product ratings
* Review volume
* Pricing
* Product category
* Listing quality

This could help determine whether weak performance is primarily a pricing issue or whether other product factors are involved.

---

# 3. Customer Reviews and Product Engagement

The number of customer reviews varied considerably across products.

The analysis also compared review counts with ratings and the project's revenue-potential measure.

### Finding

Products with higher review volumes tended to show stronger revenue potential than products with lower review volumes.

The analysis therefore suggests that review volume may be an important indicator of product engagement and commercial performance within this dataset.

### Important limitation

This analysis identifies a relationship in the data. It does **not** establish that increasing reviews will directly cause revenue to increase.

Other factors, such as product popularity, category, price and product quality, may also contribute to both review volume and performance.

### Recommendation

Customer review activity should be monitored alongside sales and product performance rather than treated as an isolated KPI.

For products with strong potential but relatively low review volumes, further investigation into customer engagement and review-generation opportunities may be worthwhile.

---

# 4. Ratings and Discounts

The analysis also examined the relationship between product ratings and discount levels.

### Finding

Products with lower ratings generally appeared alongside lower review volumes and lower discount levels in the analysis.

This provides a useful starting point for investigating whether product quality, customer perception, pricing or product visibility is contributing to weaker performance.

### Recommendation

Low-rated products should be reviewed alongside their customer feedback, pricing and listing information before increasing promotional activity.

Increasing discounts on a poorly performing product may not solve the underlying problem.

---

# 5. Electronics and Product Ratings

Electronics performed strongly in terms of potential revenue and also appeared prominently among products with high ratings.

However, strong ratings did not always correspond to the highest sales volume.

### Finding

The analysis suggests that product ratings alone are not sufficient for identifying the strongest commercial opportunities.

### Recommendation

Product evaluation should combine multiple indicators, including:

* Rating
* Review volume
* Price
* Discount
* Revenue potential
* Category

This provides a broader view of product performance than relying on a single metric.

---

# Key Findings

| Area                    | Finding                                                                   |
| ----------------------- | ------------------------------------------------------------------------- |
| Revenue potential       | Electronics recorded **over ₹87M** in potential revenue                   |
| Discounts               | Some heavily discounted products still performed poorly                   |
| Reviews                 | Higher review volumes were associated with stronger revenue potential     |
| Ratings                 | High ratings did not always correspond with the highest sales volume      |
| Low-performing products | Lower-rated products generally had fewer reviews and lower discounts      |
| Electronics             | Strong presence among highly rated products and highest potential revenue |

---

# Recommendations

Based on the analysis, I would recommend:

### 1. Review Electronics performance

Examine the Electronics category more closely to understand which products are responsible for its strong potential revenue and whether the performance translates into actual sales and profit.

### 2. Do not rely on discounts alone

Products that continue to underperform despite heavy discounts should be reviewed for other issues, including pricing, customer perception, product quality and listing visibility.

### 3. Monitor customer engagement

Review volume can provide useful information about customer engagement, but it should be considered alongside actual sales and profitability.

### 4. Investigate low-rated products

Products with low ratings and low review volumes may require further investigation before additional promotional spending is applied.

### 5. Look beyond Electronics

Although Electronics had the strongest potential revenue, other categories may contain products with strong performance that could be overlooked when attention is concentrated on the largest category.

---



# Technical Work

The project involved:

* Data cleaning
* Data quality checks
* Calculated columns
* Revenue-potential calculation
* PivotTable analysis
* Category comparisons
* Rating analysis
* Review-volume analysis
* Discount analysis
* Dashboard development

---

# Limitations

There are several limitations to consider when interpreting the findings.

### Revenue potential is not actual revenue

The project calculates potential revenue using:

**Actual Price × Rating Count**

This provides a useful comparison measure within the dataset, but it should not be interpreted as confirmed sales revenue.

### Review count is not necessarily a cause of revenue

The analysis identifies a relationship between review volume and revenue potential, but does not establish causation.

### No direct sales data

Without actual transaction-level sales data, it is not possible to determine whether the products with the highest calculated revenue potential also generated the highest realised revenue or profit.

### Product-level factors

Other variables such as product quality, brand, availability, competition and listing quality may also affect product performance but are not fully captured in this analysis.

---

# What This Analysis Shows

One of the main lessons from this project is that a product can look strong or weak depending on the measure being used.

Electronics, for example, stood out strongly when looking at potential revenue. However, high potential revenue does not automatically mean high realised sales or profitability.

Similarly, a high product rating does not necessarily mean that the product has the highest sales volume.

Looking at several measures together gives a more useful picture of product performance than relying on one metric.

---
# Dashboard

The Excel dashboard was designed to allow users to explore product performance interactively using:

* PivotTables
* Pivot Charts
* Slicers
* Calculated fields
* Category-level comparisons

The dashboard allows product categories and performance indicators to be compared without having to work directly with the raw dataset.

---
The Dashboard Pages.
![Amazon Sales Dashboard Pg 1 2](https://github.com/user-attachments/assets/fceeb2b1-eaae-4458-96f3-41a89ce629ad)
![Amazon Sales Dashboard Pg 2 2](https://github.com/user-attachments/assets/ddbbfe81-2d34-4d5d-b2e7-28b23def3c08)
![Amazon Insights and Recommendations Page](https://github.com/user-attachments/assets/6518f521-3954-477a-84f6-7d45b0a979ad)






