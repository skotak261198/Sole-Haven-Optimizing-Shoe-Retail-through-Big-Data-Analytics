# Sole Haven: Optimizing Shoe Retail through Big Data Analytics

## Overview

This project is part of the **BUDT737: Enterprise Cloud Computing and Big Data** course. We analyzed a comprehensive dataset from **Sole Haven**, a shoe retailer, to understand consumer behavior, optimize profitability strategies, and enhance customer satisfaction. By leveraging various data analysis and machine learning techniques, we aimed to provide actionable insights that Sole Haven can use to gain a competitive edge in the market.

## Executive Summary

Our analysis focused on deriving insights from a rich dataset encompassing various shoe products to optimize marketing strategies and drive profitability for Sole Haven. The project included the following key steps:

- **Data Preprocessing**: We identified and removed null values to maintain data integrity, ensuring the accuracy of all subsequent analyses.
- **Feature Engineering**: New metrics, such as "Units Sold," were created to gauge product popularity and customer preferences, allowing for tailored marketing and inventory strategies.
- **Advanced Analytics**: Using techniques like k-means clustering and PySpark GraphFrames, we performed customer segmentation and developed personalized product recommendations.
- **Real-Time Insights**: Through Spark Streaming, we explored the impact of real-time data on inventory management, pricing strategies, and customer satisfaction.

## Research Questions

1. **Optimization of Marketing Strategies**: What insights can be leveraged to optimize marketing strategies and drive sales across different customer segments?
   
2. **Enhancing Customer Segmentation**: How can we improve customer segmentation, optimize marketing, and enhance inventory management to boost competitive advantage and customer loyalty?
   
3. **Impact of Real-Time Data**: How does implementing streaming analytics affect profitability and brand reputation? Can real-time insights optimize operations and enhance customer satisfaction?

4. **Product Relationship Analysis**: How are different shoe models related based on factors like color and category? How can these relationships inform personalized recommendations and marketing?

## Methodology

1. **Data Preprocessing**: 
   - Removed null values to ensure data integrity.
   - Added columns using the `withColumn` method and generated random numbers with the `rand()` function to highlight important products and trends.

2. **Descriptive Statistics**: 
   - Summarized key attributes such as pricing, ratings, and sizes to understand data distribution and gain initial insights.

3. **Feature Engineering**: 
   - Created new features like "Units Sold" and "Revenue Generated" to evaluate product performance and identify profitability potential.

4. **Clustering Analysis (K-means)**: 
   - Segmented customers based on purchasing behavior and preferences, enabling targeted marketing and personalized recommendations.

5. **Spark Streaming**: 
   - Leveraged real-time data for dynamic marketing campaigns and improved customer experiences, focusing on inventory optimization and timely promotions.

6. **PySpark GraphFrames**: 
   - Applied graph analytics to understand product relationships, facilitating personalized recommendations and enhancing customer satisfaction.

## Key Insights

- **Revenue Optimization**: Identified high-performing products and refined profitability strategies by analyzing price and units sold.
- **Customer Segmentation**: Enhanced segmentation through k-means clustering, enabling more effective, targeted marketing strategies.
- **Real-Time Analytics**: Demonstrated the value of real-time insights for inventory management, pricing optimization, and marketing effectiveness.
- **Personalized Recommendations**: Used graph analytics to uncover relationships between products, guiding personalized marketing and enhancing customer loyalty.

## Conclusion

Our analysis provides Sole Haven with a robust framework for data-driven decision-making, optimizing operations, and boosting profitability. By understanding customer behavior, segmenting effectively, and leveraging real-time data, Sole Haven is well-positioned to enhance customer satisfaction and achieve sustained growth in the competitive shoe retail market.

## Getting Started

To explore the project and replicate our analysis:

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/sole-haven-analysis.git
