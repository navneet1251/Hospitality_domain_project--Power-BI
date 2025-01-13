
# Hospitality Domain Project - Power BI

## Project Overview

This project involves analyzing hotel booking data using five datasets: `dim_date`, `dim_hotels`, `dim_rooms`, `fact_aggregated_bookings`, and `fact_bookings`. The primary objective is to extract meaningful insights from these datasets, such as room occupancy trends, revenue generation, and customer booking behavior. 


## Files and Metadata

### Datasets:
1. **dim_date.csv**: Provides detailed information about dates, including week numbers and day types (Weekend/Weekday).
   - **Columns**:
     - `date`: Dates in May, June, and July.
     - `mmm yy`: Date in "Month Year" format.
     - `week no`: Unique week number.
     - `day_type`: Indicates if the date is a Weekend or Weekday.

2. **dim_hotels.csv**: Contains details about hotels, including categories and locations.
   - **Columns**:
     - `property_id`: Unique ID for each hotel.
     - `property_name`: Name of the hotel.
     - `category`: Hotel classification (Luxury/Business).
     - `city`: Location of the hotel.

3. **dim_rooms.csv**: Information on room types and classifications.
   - **Columns**:
     - `room_id`: Room type (RT1, RT2, RT3, RT4).
     - `room_class`: Classification (Standard, Elite, Premium, Presidential).

4. **fact_aggregated_bookings.csv**: Aggregated data on successful bookings and room capacity.
   - **Columns**:
     - `property_id`: Unique hotel ID.
     - `check_in_date`: Customer check-in dates.
     - `room_category`: Room type (RT1, RT2, RT3, RT4).
     - `successful_bookings`: Total successful bookings.
     - `capacity`: Maximum room capacity.

5. **fact_bookings.csv**: Detailed booking records for individual customers.
   - **Columns**:
     - `booking_id`: Unique booking ID.
     - `property_id`: Hotel ID.
     - `booking_date`: Booking creation date.
     - `check_in_date`: Customer check-in date.
     - `check_out_date`: Customer check-out date.
     - `no_guests`: Number of guests per booking.
     - `room_category`: Room type.
     - `booking_platform`: Platform used for booking.
     - `ratings_given`: Ratings by customers.
     - `booking_status`: Status of the booking (Cancelled, Checked Out, No Show).
     - `revenue_generated`: Revenue generated per booking.
     - `revenue_realized`: Revenue received by the hotel after deductions (if applicable).

## Key Features

- **Data Cleaning and Preprocessing**:
  - Handle missing data, inconsistencies, and outliers.
  - Standardize date formats and ensure data integrity across datasets.

- **Exploratory Data Analysis**:
  - Identify booking trends and patterns across different room types, hotels, and time periods.
  - Analyze weekend vs. weekday booking behavior.

- **Revenue Analysis**:
  - Calculate revenue generated and realized based on booking statuses.
  - Visualize revenue trends across different hotel categories and locations.

- **Customer Insights**:
  - Evaluate customer satisfaction based on ratings.
  - Study booking preferences by platform and guest count.


## Visualization

The project includes interactive and static visualizations for:
- Booking trends over time.
- Revenue breakdown by hotel and room categories.
- Ratings distribution by booking platforms.

## Future Scope

- Implement predictive models to forecast booking trends.
- Incorporate more datasets for a broader analysis.

## License

This project is licensed under the MIT License.

---
