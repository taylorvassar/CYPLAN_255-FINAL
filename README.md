# Spacing SF: Examining Inequity in Access to Essential Amenities

Welcome! This project investigates the distribution of public amenities among socioeconomically diverse census tracts in San Francisco. Our main research question is: *How are key neighborhood amenities distributed across socioeconomically different areas of San Francisco, and do these spatial patterns produce compounded disadvantage?*

Check out our ArcGIS Storymap here!
All work by Taylor Vassar and Brittany Vang.

# Reproducibility
In order to reproduce your own version on your device, do the following steps:

**1.** Run git clone https://github.com/taylorvassar/Spacing_San_Francisco.git in your terminal. \
**2.** You now have access to the datasets and visuals that we have used!

**Pro Tip:** If you recieve a 'module not found' error, try running **pip install (module name)** in your terminal.

# Data 
This project utilizes datasets from several sources. Below is a table that summarizes the information. For the SNAP Retailers dataset that is accessed via PolicyMap, the user may need to sign in with their institutional credentials or create an account.
## Datasets
| Dataset | Year Coverage | Size (Disk) | Source |
| ------- | ------------- | ------ | ------- |
| SF Census Tract | 2020 | 382 KB | [DataSF](https://data.sfgov.org/Geographic-Locations-and-Boundaries/Census-2020-Tracts-for-San-Francisco/tmph-tgz9/about_data) |
| Medium Income of Census Tracts | 2020-2024 | 23.03 KB | [US Census Bureau](https://www.census.gov/programs-surveys/acs/news/data-releases/2024/release.html#fiveyear) |
| Active Food Services | 1960-2026 | 41.53 KB | [DataSF](https://data.sfgov.org/Economy-and-Community/Active-Food-Services/q484-t4an) |
| SNAP Retailers | 2020-2025 | 84.93 KB | [PolicyMap](https://www.policymap.com/data/sources/united-states-department-of-agriculture-usda-agricultural-marketing-service) |
| Mobile Food Services | 2015-2026 | 292.5 KB | [Open Data SF](https://opendatasanfrancisco.com/mobile-food-facilities#results) |
| Muni Stops | 2025 | 820.09 KB | [DataSF](https://data.sfgov.org/Transportation/Muni-Stops/i28k-bkz6/about_data) |
| School Locations | 2024-2025 | 29 MB| [NCES](https://nces.ed.gov/programs/edge/Geographic/SchoolLocations) |

# Findings

We discovered some interesting patterns within each category. Here's a snapshot of them.

## Census Tract + Income
- Major income inequality across San Francisco's census tracts, ranging from $18,217 to $247,500 
- Wealthier areas cluster in the north while lower-income tracts concentrate in the center and southeast
## Food
## Transit (Muni)
- Map of Muni transit stops reveals dense coverage across the northeastern quadrant of San Francisco, mostly in Downtown and the Financial District
- Coverage thins noticeably toward the southwestern areas, suggesting lower transit frequency 
- When transit stops are overlaid on the median income layer, distribution is seemingly patternless
-  Middle income central tracts benefit from the densest stop coverage, while the lowest income tracts show fewer stops, pointing to a compounded disadvantage. 

## Public Schools
- On average, census tracts are about 405 meters from the nearest public school, and half of all tracts are within 366 meters, which is roughly a 5-minute walk
- Schools are much more densely clustered in the central and eastern parts of the city
- Some southern tracts near Bayview show moderate school proximity despite lower income levels, suggesting school access may not be the primary driver of disadvantage there
# Conclusion
Overall, we found that income by itself does **not** strongly predict access to any single type of amenity. Some low-income neighborhoods still have nearby services, while some higher-income areas are not uniformly well served. However, when we combine food, transit, and school access into a single index, clearer patterns emerge. Certain parts of the city experience overlapping gaps across multiple services at once, especially in specific western and southeastern tracts. These patterns would not be visible if we only looked at one type of amenity at a time, which supports the idea that deprivation builds across different parts of everyday life rather than appearing in isolation.

**Policy Considerations:** This suggests that treating food access, transit access, and educational access as separate problems can miss where the biggest needs actually are. A more effective approach would focus on neighborhoods where multiple disadvantages overlap, rather than addressing each system independently. For example, improving transit connectivity, increasing high-quality food options, and strengthening school resources in the same areas could have a greater combined impact on opportunity.

**Future Research:** More broadly, this project shows why it is important to measure urban inequality in a way that reflects real lived experience, where people rely on several systems at once. It also suggests future research could look more closely at how these overlapping disadvantages affect outcomes like health, mobility, and long-term opportunity over time.








