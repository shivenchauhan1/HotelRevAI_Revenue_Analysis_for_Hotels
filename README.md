🏨 HotelRevAI: AI-Driven Revenue Analysis for Hotels
An intelligent analytics system designed to monitor, analyze, and optimize hotel revenue and occupancy performance using data-driven insights. This project was developed as part of the Infosys Springboard Virtual Internship 6.0.

📖 Project Overview
The hospitality industry generates immense amounts of booking and customer data. The goal of HotelRevAI is to transform this raw data into actionable intelligence. By integrating data modeling, performance metrics, guest analysis, and forecasting into a unified Power BI dashboard, this project empowers hotel stakeholders (General Managers and Revenue Managers) to optimize pricing, reduce cancellation risks, and boost overall profitability.

🛠️ Tech Stack & Tools
Business Intelligence: Power BI (Interactive Dashboards, Data Modeling)

Data Processing: Power Query (M Language for data cleaning, merging, and automated data generation)

Analytics Engine: DAX (Data Analysis Expressions for custom KPIs and clustering logic)

Data Source: Microsoft Excel / CSV

📊 Key Modules & Dashboards
1. Executive Performance Overview (General Manager Dashboard)
Provides a high-level snapshot of overall hotel health across multiple branches.

Core KPIs Tracked: RevPAR (Revenue Per Available Room), ADR (Average Daily Rate), Occupancy Rate %, and Total Revenue.

Insights: Branch-wise revenue contribution, channel distribution (OTA vs. Direct vs. Corporate), and weekday vs. weekend booking trends.

2. Guest Behavior & Customer Clustering (Module 3)
Deep dive into who is booking and why, using RFM (Recency, Frequency, Monetary) principles to segment guests.

Guest Segmentation: Categorized travelers into Business, Family, Solo, and Corporate based on stay duration and purpose.

Behavioral Clustering (DAX Implementation): Segmented guests dynamically into categories like "First-Timer", "Loyal Guest", and "High Spender" based on their historical spend and booking frequency.

Demographics: Visualized nationality spread and booking sources to identify high-value geographic markets.

3. Forecasting & Cancellation Trends (Module 4)
Identifying unreliable bookings and projecting future demand.

Cancellation Analytics: Created logic to track CancellationFlag, NoShowFlag, and LeadTime to map out the likelihood of guests dropping out based on how early they booked.

Demand Forecasting: Utilized Power BI's built-in 7-month forecasting model with a 95% confidence interval to provide visibility into future occupancy trends, aiding in dynamic pricing and staff planning.

4. Revenue Strategy & Ancillary Revenue (Module 5)
Looking beyond room rates to maximize total customer value.

Ancillary Tracking: Modeled non-room revenue streams like Spa, Dining, and Other Services using custom M-code to generate realistic transaction data.

Upsell Performance: Evaluated the impact of discounts on overall revenue and modeled dynamic pricing logic to support tactical revenue management.

🚀 How to Run the Project
Clone this repository to your local machine.

Ensure you have Power BI Desktop installed.

Open the Hotel_Final.pbix file.

(Optional) To view the raw data and transformations, click on Transform Data to open the Power Query Editor.

👨‍💻 About the Author
Shiven Pratap Singh
B.Tech in Computer Science and Engineering | Lovely Professional University
Passionate about turning complex datasets into clear, strategic business insights. Proficient in C++, Java, Python, and data analytics.
