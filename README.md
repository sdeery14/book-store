# Book Pricing Optimization Analysis

## Overview

This repository contains an analysis aimed at determining the optimal pricing strategy for the sequel to "Harry Potter and the Deathly Hallows" for the Book Emporium. Using historical sales data and regression models, we predict the demand curve for the new book and explore various pricing scenarios to maximize profit under different cost conditions.

## Report Contents

### 1. Regression Analysis

- **Graphical Representation**:
  - Plotted the percentage of customers purchasing the book against different price points.
- **Power Regression Model**:
  - Derived the equation \( y = 14.098x^{-1.872} \) where \( y \) is the percentage of customers purchasing and \( x \) is the price.
  - Achieved a high R² value of 0.9919, indicating that 99% of the variance in the purchase percentage is explained by the price.

- **Predicted Sales**:
  - Estimated sales based on a customer base of 100,000 visitors.
  - Calculated revenue and profit for each price point, considering a fixed publisher cost of $5.00 per book.

### 2. Optimization Analysis with Constraints

- **Highest Profit Calculation**:
  - Scenario 1: Selling books at $10.74 with a $5.00 cost results in 16,555 books sold and a profit of $95,070.
  - Scenario 2: Selling books at $7.82 with a $4.50 cost (for 30,000 books) results in 30,000 books sold and a profit of $99,587.
  - Scenario 3: Selling books at $5.95 with a $4.00 cost (for 50,000 books) results in 50,000 books sold and a profit of $97,607.
  
- **Optimal Solution**:
  - Scenario 2 offers the highest profit of $99,587. The optimal price to charge is $7.82, and the cost paid to the publisher is $4.50 per book for orders of at least 30,000 books.

### 3. Discussion

- **Risks of Using Historical Data**:
  - The primary risk is assuming that the demand for the sequel will mirror that of "Harry Potter and the Deathly Hallows" released nearly 12 years ago.
  - Changes in market dynamics, consumer preferences, and the broader economic environment could significantly impact demand.

- **Additional Data Requirements**:
  - Insights into the current reading and purchasing behaviors, trends in physical vs. digital book sales, and J.K. Rowling's ongoing public presence.
  - Historical sales data for previous Harry Potter books, Bloomsbury Publishing, and comparable genres to better understand market expectations.
  - Analysis of marketing expenditures and their impact on sales for J.K. Rowling's previous releases.

### 4. Additional Considerations

- **Pricing Strategy**:
  - Flexibility in pricing to accommodate shifts in demand and competitive pressures.
  - Consideration of different formats (e.g., hard copy vs. digital) and their respective demand curves.

- **Market and Competitive Analysis**:
  - Understanding the impact of social media, public sentiment towards J.K. Rowling, and broader trends in book publishing and sales.
  - Evaluating the potential influence of economic factors, such as recessions, on consumer purchasing behavior.

## Authors
- Sean Deery
- Frank Bryn
- Christian Dobish
- Leonard Lasek


## How to Use This Repository

1. **Explore Data and Analysis**: Check the book-store-analysis.xlsx file for a detailed walkthrough of the pricing optimization process and visualizations.
2. **Review the Full Report**: Go to the book-store-report.docx file to read the comprehensive analysis on pricing strategies and recommendations.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
