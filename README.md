# 🚖 OLA Rides — Data Analyst Project

![SQL](https://img.shields.io/badge/SQL-MySQL-blue?style=flat&logo=mysql)
![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=flat&logo=powerbi)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

An end-to-end data analysis project simulating **1,00,000 OLA ride bookings** in Bengaluru over one month, analyzed using **SQL** and visualized in **Power BI**.

---

## 📊 Dataset Highlights

- **100K rows** of synthetic ride data across 19 columns
- Booking ID format: `CNR` + 10 digits
- 50 real Bengaluru areas as pickup/drop locations
- Vehicle types: Auto, Mini, Bike, eBike, Prime Sedan, Prime Plus, Prime SUV

**Key business rules applied:**

| Rule | Value |
|------|-------|
| Successful bookings | 62% |
| Customer cancellations | ≤ 7% |
| Driver cancellations | ≤ 18% |
| Incomplete rides | < 6% |
| Orders under ₹500 | 70% |
| Higher volume on | Weekends & Match Days |

---

## 🛢️ SQL Analysis (MySQL)

10 analytical views created, covering:

- Successful bookings retrieval
- Average ride distance by vehicle type
- Top 5 customers by ride count
- Driver cancellations by reason
- Max/Min driver ratings for Prime Sedan
- Total revenue from successful rides
- Incomplete rides with reasons

---

## 📈 Power BI Dashboard

5 report pages built:

| Page | Visuals |
|------|---------|
| **Overall** | Ride volume over time, Booking status breakdown |
| **Vehicle Type** | Distance & revenue by vehicle type |
| **Revenue** | Revenue by payment method, Top 5 customers |
| **Cancellation** | Customer & driver cancellation reasons |
| **Ratings** | Driver & customer ratings by vehicle type |

**Snapshot metrics:**
- Total Bookings: **99,673** | Revenue: **₹34M**
- Cancellation Rate: **28%** | Avg Rating: **~4.0**
## 🖼️ Dashboard Screenshots

### Overall View
![Overall](https://github.com/naanibabu/OLA-Data-Analysis/blob/main/dashboard%20-1.png)

### Vehicle Type View
![Vehicle Type](https://github.com/naanibabu/OLA-Data-Analysis/blob/main/dashboard-2.png)

### Revenue View
![Revenue](https://github.com/naanibabu/OLA-Data-Analysis/blob/main/dashboard-3.png)

### Cancellation View
![Cancellation](https://github.com/naanibabu/OLA-Data-Analysis/blob/main/dashboard-4.png)

### Ratings View
![Ratings](https://github.com/naanibabu/OLA-Data-Analysis/blob/main/dashboard%20-5.png)

---
## 🛠️ Tools Used
`MySQL` &nbsp;|&nbsp; `Power BI` &nbsp;|&nbsp; `Excel`
