# Seattle Airbnb Market Analysis in Tableau

![Seattle Airbnb Market Analysis.png](https://github.com/ndomah1/Seattle-Airbnb-Market-Analysis-in-Tableau/blob/main/images/Seattle%20Airbnb%20Market%20Analysis.png)

Click [here](https://public.tableau.com/app/profile/nilesh.domah4581/viz/SeattleAirbnbMarketAnalysis_17423423549360/Dashboard1) to view interactive dashboard on Tableau Public.

## Overview

This project analyzes Seattle Airbnb properties using Tableau to determine price trends, geographic location, and revenue patterns. The dashboard provides insights regarding average prices per number of bedrooms, price disparities across zip codes, and revenue over time.

## Objectives and Key Questions

- What is the average price per bedroom in Seattle?
- How do prices change by zip code?
- How does revenue fluctuate throughout the year?
- What is the distribution of listings by bedroom count?

## Dataset

The dataset (available on [Kaggle](https://www.kaggle.com/datasets/airbnb/seattle)) consists of Airbnb properties with the following details:

- **Listing ID**: Unique identifier for each property.
- **Zipcode**: Geographic location of the listing.
- **Price**: Nightly rate for the property.
- **Bedrooms**: Number of bedrooms per listing.
- **Revenue**: Total revenue generated annually.
- **Reviews**: Guest feedback and ratings on the property.

## Key Insights

### 1. Average Price per Bedroom

- Single-bedroom properties have an average price of **$96.2** per night.
- Prices increase with the number of bedrooms, reaching an average of **$584.8** for six-bedroom homes.

### 2. Price Distribution by Zip Code

- Zip codes **98177, 98112, and 98109** have the highest average prices.
- More affordable options are available in areas like **98108 and 98118**.

### 3. Revenue Trends Over Time

- Revenue follows an upward trend throughout the year.
- Peaks occur during **summer months and holidays**.
- The lowest revenue periods are typically **January and February**.

### 4. Listings Distribution by Bedroom Count

- The majority of Airbnb listings are **one-bedroom properties (1,811 listings)**.
- The number of available properties decreases as the bedroom count increases.
- **Larger homes (4+ bedrooms) are less common** but command higher prices.

## Tableau Dashboard

The interactive **Tableau dashboard** includes:

- **Average price per bedroom** (bar chart)
- **Price variations across zip codes** (map and bar chart)
- **Revenue trends over time** (line chart)
- **Listings distribution by bedroom count** (table and bar chart)

![Seattle Airbnb Market Analysis.png](https://github.com/ndomah1/Seattle-Airbnb-Market-Analysis-in-Tableau/blob/main/images/Seattle%20Airbnb%20Market%20Analysis.png)

## Usage Instructions

- Access the Tableau dashboard [here](https://public.tableau.com/views/SeattleAirbnbMarketAnalysis_17423423549360/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link**).
- Use filters to explore data by **zip code and bedroom count**.
- Interact with charts to **dive deeper into specific trends**.

## Limitations

- **Freshness of Data**: The dataset may not reflect current market trends, as Airbnb prices fluctuate frequently.
- **Missing Variables**: The analysis does not consider factors like property amenities, seasonality beyond revenue trends, or host-specific pricing strategies.
- **Geographic Resolution**: Zip codes provide a broad segmentation, but neighborhood-level insights could offer a more detailed view of pricing trends.
- **Revenue Accuracy**: Revenue data is based on available records and may not account for discounts, cancellations, or additional fees.

## Future Recommendations

- **Further Geographic Analysis**: Explore price variations at the neighborhood level.
- **Predictive Modeling**: Use historical data to forecast future prices.
- **Host Profitability Analysis**: Identify the most profitable property types and locations.
- **Customer Sentiment Analysis**: Analyze Airbnb reviews to assess guest satisfaction trends.

This project highlights how **Tableau can be leveraged** to gain insights into the short-term rental market and develop informed pricing strategies.
