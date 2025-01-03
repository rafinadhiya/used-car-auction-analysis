# 🚗 Used Car Auction Data Analysis

This project explores the data from used car auctions, aiming to uncover patterns and factors influencing auction outcomes. The insights derived from this analysis can provide valuable information for stakeholders in the automotive industry.

---

## 🌟 Problem Statement

This study aims to determine and implement the appropriate strategy based on key factors such as grade, brand, age, odometer, production year, promotions, sales location, and seller performance to improve the profitability of used car auctions. The target is to achieve 70% of sales above market price within 6 months while avoiding losses and maintaining profit margins. The used car auction data used originates from the period 2014 to 2015, and the study results are expected to provide practical insights for business decision-making at the beginning of 2025.

---

## 🎯 Objectives

1. 📊 Perform data exploration to understand key characteristics of auctioned vehicles.
2. 🔍 Identify factors potentially affecting auction profitability.
3. 📈 Create engaging data visualizations to support analysis and storytelling.

---

## 📂 Dataset

| No  | Column           | Description                                                                                                   |
| :-: | --------------- | ----------------------------------------------------------------------------------------------------------- |
| 1   | vin             | Vehicle Identification Number (VIN), a unique identifier for each car.                                       |
| 2   | year            | The year the car was manufactured.                                                                           |
| 3   | brand           | The car's brand or manufacturer (e.g., Kia, BMW, Volvo).                                                     |
| 4   | model           | The specific model of the car (e.g., Sorento, 3 Series, S60).                                                |
| 5   | bodytype        | The type of the car's body (e.g., SUV, Sedan).                                                               |
| 6   | transmission    | The car's transmission type (e.g., automatic).                                                               |
| 7   | condition       | A numerical value indicating the car's condition.                                                            |
| 8   | grade           | The category or class of the car's condition, derived from rounding the value in the 'condition' column.     |
| 9   | odometer        | The number of miles or kilometers the car has traveled (mileage).                                            |
| 10  | color           | The car's exterior color.                                                                                    |
| 11  | interior        | The car's interior color.                                                                                    |
| 12  | state           | The state code where the car is sold (e.g., 'CA' for California).                                            |
| 13  | seller          | The seller or entity responsible for selling the car.                                                        |
| 14  | marketvalue_mmr | Manheim Market Report value (the car's wholesale market price).                                              |
| 15  | sellingprice    | The price at which the car was sold.                                                                         |
| 16  | price_diff      | The difference between the car's selling price and its market value (Market Value / MMR).                   |
| 17  | auction_outcome | A category based on the value in the 'price_diff' column, indicating whether the car sold above or below market value. |
| 18  | brand_encoded   | The result of converting the car brand names into numbers to facilitate numerical analysis.                  |
| 19  | grade_encoded   | The result of converting the 'grade' categories (car condition) into numbers for statistical analysis.       |
| 20  | car_age         | The car's age in years, calculated from the manufacturing year to the selling year.                          |
| 21  | saledate        | The exact date when the car was sold.                                                                        |
| 22  | day             | The day of the week when the sale occurred (e.g., Monday, Tuesday).                                          |
| 23  | day_category    | The category of the sale day, such as weekend or weekday.                                                    |
| 24  | month           | The name of the month when the sale occurred (e.g., December, January).                                      |
| 25  | sale_year       | The year when the sale occurred.                                                                             |
| 26  | date            | The specific sale date (e.g., December 16, 2024).                                                            |
| 27  | hour            | The hour at which the sale occurred.                                                                         |
| 28  | month_number    | The numerical representation of the sale month (1 for January, 2 for February, etc.).                        |
| 29  | quarter         | The quarter of the year in which the sale occurred (Q1, Q2, Q3, or Q4).                                      |

---

## 🛠️ Methodology

1. **🧹 Data Cleaning:**
   - Handle missing values, duplicates, and inconsistencies.
2. **📊 Data Exploration:**
   - Analyze data distribution and variable correlations.
3. **🎨 Visualization:**
   - Use Tableau to create interactive dashboards.

---

## 🛠️ Tools Used

- **🐍 Python:** Pandas, NumPy, Matplotlib, Seaborn.
- **📊 Tableau:** For interactive visualizations.
- **📒 Jupyter Notebook:** For documenting and presenting the analysis.

---

## 🚀 Key Insights

To enhance the profitability of used car auctions, it is important to consider several factors such as **grade, brand, odometer, car age, promotions, and sales location.**

- **Luxury Cars:** Prioritize luxury cars with low grades, as they maintain high selling prices compared to cars with higher grades.
- **Low Odometer and Age:** Focus on cars with low odometer readings, ages of 0-5 years, and good grades for higher profitability.
- **Promotions:** Carefully manage promotions to generate short-term profits while ensuring long-term stability with a balanced strategy.
- **Top States:** Sales in the top 5 states with the highest average prices can accelerate and optimize profit.

By implementing this strategy, it is expected that **70% of vehicles can be sold within 6 months at prices no more than 5% below the market value (MMR).**

---

## 🌐 External Links

- **Source:** [Vehicle Sales Data](https://www.kaggle.com/datasets/syedanwarafridi/vehicle-sales-data)
- **Tableau Link:** [Tableau Used Car Auction Analysis](https://public.tableau.com/views/milestoneafi/UsedCarAuctionAnalsis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- **Google Drive Links for Datasets:**
  - [car_prices.csv (original Kaggle dataset)](https://drive.google.com/file/d/1WnVBdCS_rKHVu241Q8N_jnAHVq0fvx9x/view?usp=drive_link)
  - [car_prices_clean_data.csv (cleaned dataset)](https://drive.google.com/file/d/1UKKUqgYVdnfZ6QpRPrV8HDyuZ3cD7lUy/view?usp=drive_link)

---

## 👩‍💻 About the Developer

Developed by **[Rafina Dhiya Pradani]**  
📧 [Email](mailto:rafina.pradani@gmail.com) | 🌐 [LinkedIn](https://www.linkedin.com/in/rafinadhiya/)  

---

Feel free to reach out with any questions or feedback! 😊

---