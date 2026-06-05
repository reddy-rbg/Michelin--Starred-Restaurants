# Michelin-Starred Restaurants Analytics

![Tableau](https://img.shields.io/badge/Tableau-Dashboard-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Data](https://img.shields.io/badge/Dataset-Michelin%20Restaurants-8B0000?style=for-the-badge)
![Analytics](https://img.shields.io/badge/Focus-Global%20Dining%20Insights-1F6FEB?style=for-the-badge)

A Tableau-centered analytics project exploring Michelin-starred restaurants around the world through cuisine, geography, award level, and price range. The project turns a restaurant dataset into a visual story about where fine dining clusters, which cuisines dominate, and how prices vary across culinary styles.

## Project Story

The analysis is built around four questions:

1. Where are Michelin-starred restaurants located?
2. Which cuisine categories appear most often?
3. How do minimum and maximum prices vary by cuisine?
4. How are award levels distributed across the restaurant landscape?

## Repository Map

| Path | Purpose |
| --- | --- |
| `Michelin -Starred Restaurants/restaurants_data.csv` | Source dataset with location, cuisine, award, URL, and price fields. |
| `Michelin -Starred Restaurants/project.twb` | Tableau workbook for the dashboard and worksheets. |
| `Michelin -Starred Restaurants/analysis.txt` | Analysis notes and visualization direction. |
| `Michelin -Starred Restaurants/Poreddy Ajay Kumar Reddy_Report.docx` | Written project report. |
| `Michelin -Starred Restaurants/Michelin-Starred Restaurants Across the Globe _Poreddy Ajay.pptx` | Presentation deck. |

## Dataset Fields

The dataset includes:

- Restaurant name, address, and city/location
- Cuisine type
- Longitude and latitude for mapping
- Phone number and Michelin Guide URL
- Award category such as `1 MICHELIN Star`, `2 MICHELIN Stars`, or `3 MICHELIN Stars`
- Minimum and maximum price in USD

## Dashboard Ideas

| View | Insight |
| --- | --- |
| Global map | Shows geographic concentration of Michelin-starred restaurants. |
| Cuisine distribution | Reveals dominant cuisines and niche specialties. |
| Price range by cuisine | Compares affordability and premium dining categories. |
| Award frequency | Highlights how rare higher-star awards are within the dataset. |

## Key Insights

- Creative, modern, French, and other fine-dining cuisines tend to appear in premium price bands.
- Some cuisine categories show wide price variation, which suggests both accessible and luxury experiences within the same label.
- Geographic mapping helps reveal fine-dining clusters around major culinary cities.
- Award-level comparison adds context beyond price, showing that higher cost does not automatically equal higher star rating.

## How To Explore

1. Open `project.twb` in Tableau.
2. Connect or refresh the workbook against `restaurants_data.csv`.
3. Review the worksheets for geography, cuisine mix, price range, and award distribution.
4. Use filters for cuisine, location, and award level to explore specific dining segments.

## Suggested Enhancements

- Add country-level grouping for cleaner geographic comparisons
- Create price-per-star metrics
- Add interactive filters for cuisine and award level
- Build a final executive dashboard with map, price, and cuisine panels
