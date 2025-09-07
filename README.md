🏠 Airbnb Dynamic Pricing Recommendation Engine

📌 Objective

This project builds a pricing recommendation engine for Airbnb listings using historical listing data. The goal is to help Airbnb hosts set optimal prices based on data such as location, room type, reviews, and availability.

🛠 Tools & Technologies

Python (Google Colab) – Data Cleaning, EDA, Modeling
Pandas, NumPy, Scikit-learn – Data Processing & Linear Regression
Tableau – Dashboard and Visualizations
Excel – Initial data exploration (optional)
📂 Dataset

Size: ~100,000 listings
Key columns: price, room_type, neighbourhood_group, availability_365, number_of_reviews
🧹 Data Preprocessing (Python)

Size: ~100,000 listings
Key columns: price, room_type, neighbourhood_group, availability_365, number_of_reviews
🧹 Data Preprocessing (Python)

Removed nulls, duplicates, and irrelevant columns
Handled outliers in price using IQR filtering
Encoded categorical variables
Converted string-formatted prices to numeric

Average Price by Room Type
Average Price by Neighbourhood Group
Reviews vs Price Scatter
Price Distribution Histogram
Predicted vs Actual Price
Price vs Number of Reviews
Filters: Room Type, Neighbourhood, Reviews, Availability
🖼 Dashboard Screenshot
Dashboard1.png

🧠 Key Insights

Manhattan listings are the most expensive.
Hotel rooms have the highest average price.
Private rooms with many reviews are priced lower but get booked more.
Listings with higher availability tend to have more competitive pricing.
💡 Recommendations

Hosts in premium areas (like Manhattan) can maintain higher prices.
Listings in low-review areas should reduce pricing to improve occupancy.
Entire homes with strong reviews can raise prices slightly.
Dynamic pricing should consider availability, seasonality, and reviews.
📄 Deliverables

✔ cleaned_airbnb_data.csv
✔ Python .py script with data cleaning and regression model
✔ Tableau dashboard (public or image)
✔ Final PDF report with cover page, visuals, and recommendations
Exported cleaned dataset to CSV
📈 Tableau Dashboard Highlights
