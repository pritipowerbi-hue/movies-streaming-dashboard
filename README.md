
# Movies Streaming Analytics Dashboard

An interactive Power BI dashboard that analyses 5,000 movie viewing records from 2025.
It shows viewing trends, revenue, ratings and completion rates across devices,
countries and subscription plans.

![Movies Dashboard](Screenshot%202026-10-22%20145019.png)

## Key Questions Answered
- Which movies are watched the most?
- Which device and country drive the most viewing?
- How does revenue differ by subscription plan?
- How do viewing and revenue change month by month?

## Dataset
| Column | Description |
|---|---|
| ViewingID | Unique viewing record |
| UserID, MovieID | User and movie identifiers |
| WatchDate | Date of viewing (Jan to Dec 2025) |
| WatchMinutes | Minutes watched |
| CompletionPercent | How much of the movie was finished |
| Rating | User rating (1 to 5) |
| Device | Mobile, Smart TV, Laptop, Tablet |
| Country | 10 countries |
| SubscriptionPlan | Free, Basic, Standard, Premium |
| Revenue | Revenue from the viewing |

## Files
- `New movies dashboard.pbix`: Power BI report
- `Movies_dataset.xlsx`: dataset

## Tools
Power BI, Power Query, DAX, Excel

## How to open
Download the .pbix file and open it in Power BI Desktop.
