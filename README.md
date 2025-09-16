Hotel Booking Analysis

This project analyzes hotel booking data from a city hotel and a resort hotel, including details such as bookings, cancellations, guest demographics, length of stay, and other booking-related information.
The goal is to perform Exploratory Data Analysis (EDA) to identify key trends and provide insights that can help hotels optimize operations and increase revenue.

📌 Project Overview

Type of hotels: City Hotel and Resort Hotel

Data size: 119,390 rows × 32 columns

Key details: bookings, cancellations, stay duration, guests, meals, room types, deposit types, customer types, agents, and more.

Objective: Understand hotel booking patterns, analyze cancellation behavior, and derive insights that can help improve hotel revenue strategies.

🛠️ Tools & Libraries

Programming Language: Python

Notebook: Jupyter Notebook

Libraries: Pandas, NumPy, Matplotlib, Seaborn

📂 Dataset

Source URL: Hotel Booking Demand Dataset (Kaggle)

The dataset contains booking information for both hotel types, including guest details, length of stay, deposit types, meal preferences, and more.

🔧 Data Cleaning & Preparation

Handling Missing Values

Replaced missing values in company and agent with 0.

Filled missing country values with "others".

Filled missing children values with column mean.

Removing Duplicates

Dropped duplicate rows to ensure data quality.

Data Type Corrections

Converted children, company, and agent columns to integers.

Feature Engineering

Created Total_stay = weekday nights + weekend nights.

Created Total_members = adults + children + babies.

Outlier Handling

Removed extreme values in average_daily_rate (adr).

📊 Exploratory Data Analysis (EDA)

Key questions addressed:

Which hotel has more bookings?

What is the monthly and yearly booking trend?

Which meal type is most preferred?

What is the country-wise distribution of guests?

Which agent makes the most bookings?

Which room types are most demanded and most profitable?

How long do people usually stay in hotels?

Which deposit types are preferred?

What are the cancellation rates, and how do they relate to lead time?

How does the average daily rate (ADR) vary across months and per person?

Which booking channels are most used?

Do customers return for repeat bookings?

What customer types are most common?

📈 Visualizations Used

Bar Plots

Line Plots

Pie Charts

Scatter Plots

Heatmaps

Box Plots

✅ Key Insights

City Hotel accounts for ~61% of bookings, making it busier than Resort Hotel.

July–August are the busiest and most profitable months.

Bed & Breakfast (BB) is the most popular meal type.

Most guests are from European countries, especially Portugal.

Agent 9 handled the maximum bookings.

Room Type A is most demanded, while Types H, G, and C generate higher ADR.

Average stay is less than 4 days; City Hotel is preferred for short stays, Resort Hotel for longer stays.

TA/TO channel is the most used booking channel.

Cancellation rates are higher in City Hotel; long lead times increase cancellation probability.

Repeat guests are very few — retention rate is low.

Couples (two adults) form the majority of bookings.

⚡ Challenges

Large number of missing values.

Presence of duplicate data.

Some columns had incorrect data types.

Choosing the most effective visualization methods.

📌 Conclusion

City Hotel is busier and generates slightly more revenue than Resort Hotel.

Hotels should focus on Room Types A and H to balance demand and profitability.

Marketing efforts should target peak months (May–August) for maximum revenue.

Retention strategies are needed, as repeat customer rates are very low.

Offering special couple-focused packages can increase satisfaction and revenue.

Long-stay customers could be given discounts since longer stays usually reduce ADR.
