# Shark Tank India Investment Analysis (Seasons 1, 2 & 3)

An in-depth analysis of investment trends on Shark Tank India, covering total investments, average deal values, success rates, offers received, and total ask amounts across three seasons. This dashboard provides a comprehensive overview of the investment landscape on the show.

![Shark Tank Analysis](https://github.com/rahejagarvit/SharkTankIndia-PowerBI/blob/main/SharkTankIndia-Investment_Analysis/SharkTankIndia-Investment_Analysis.png)

## Data Source

The data was obtained from [this Kaggle dataset](https://www.kaggle.com/datasets/thirumani/shark-tank-india).

## Key Insights

*   **Total Investment:** Provides the total amount of money invested across all three seasons of Shark Tank India.
*   **Average Deal Value:** Shows the average size of the deals made on the show.
*   **Deal Success Rate:** Highlights the percentage of startups that received and accepted offers from the Sharks.
*   **Investment Trends by Season:** Visualizes how investment amounts and deal activity varied across seasons 1, 2 and 3.
*   **Ask vs. Invested Amount:** Compares the total amount of money requested by startups to the total amount actually invested by the Sharks, revealing negotiation outcomes.

## How to Use

1.  Download the `SharkTankIndia-Investment_Analysis.pbix` file.
2.  Open the file in Power BI Desktop.
3.  Interact with the dashboard by using the slicers (e.g., Season Number) and filters to explore specific investment trends.
4.  Hover over visuals for detailed tooltips and insights.

## Tools Used

*   Power BI Desktop
*   Microsoft Excel (for initial data cleaning and preparation)

## Data Dictionary

*   `Season Number`: The season of Shark Tank India in which the pitch occurred.
*   `Startup Name`: The name of the company that pitched on the show.
*   `Original Ask Amount`: The amount of money (in INR) that the startup initially requested from the Sharks.
*   `Total Deal Amount`: The total amount of money (in INR) that the startup received from the Sharks (if a deal was made).
*   `Received Offer`: Indicates whether the startup received an offer from any of the Sharks (Yes/No).
*   `Accepted Offer`: Indicates whether the startup accepted the offer made by the Sharks (Yes/No/Offer Not Received).
    *   "Yes": Offer was received and accepted
    *    "No": Offer was received and not accepted
    *    "ONR": Offer not received
*   `Total Deal Amount (Cr)`: The total amount of money actually invested in a deal in crores.
*   `Number of Deals Per Season`: The count of deals happening in a particular season
*   `Deals Accepted vs Rejected`: The count of deals accepted by the sharks and count of deals rejected by the sharks
*   `Accepted offers status per season`: The number of deals accepted and offers rejected per season
*    `Success Rate %`: The total success rate of offers being accepted

## Author

Garvit Raheja
