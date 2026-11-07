# Task 6 – Executive Netflix Analytics Dashboard

## Project Overview

This project brings together key analyses of the Netflix titles dataset in an executive-style Excel dashboard. It combines content distribution, country representation, release-year trends, and audience-rating analysis to present an overview of the catalogue and support business-focused interpretation.

The dashboard workbook contains a consolidated analysis sheet and a dashboard sheet with four visual reports and slicer controls.

## Task Description

**Task 6 (Advanced) – Executive Netflix Analytics Dashboard**

Create a comprehensive Excel dashboard providing business insights and performance metrics.

## Task Workflow

1. **Consolidate all analyses** – Bring the key results from the earlier tasks into a central analysis workbook.
2. **Design a professional dashboard layout** – Arrange the visual reports so that the main findings can be reviewed together.
3. **Add KPIs, charts, and slicers** – Use headline measures, charts, and filters to make the report easier to explore.
4. **Implement dynamic reporting** – Use interactive filters to examine different views of the data.
5. **Present strategic recommendations** – Translate the analysis into practical business observations and recommendations.

## Key Features

- Executive-style dashboard
- Consolidated analysis
- Content-type comparison
- Country representation visual
- Release-year trend chart
- Audience-rating comparison
- Slicer-based filtering
- Business insights and strategic recommendations

## Skills Demonstrated

- Dashboard development
- Advanced Excel visualization
- PivotTable-based analysis
- Interactive reporting
- Data storytelling
- Executive reporting
- Business insight communication

## Tool Used

- Microsoft Excel

## Dataset Overview

The project uses a Netflix titles dataset containing **8,790 records**:
- **6,126 Movies** (approximately 69.7%)
- **2,664 TV Shows** (approximately 30.3%)

The workbook organizes the consolidated analysis into a separate worksheet and presents the visual reports on the dashboard worksheet.

## Dashboard Components

The Dashboard worksheet contains four charts:

1. **Movies vs. TV Shows** – compares the two main content types.
2. **Top 10 Countries** – presents country representation in the catalogue.
3. **Movies and TV Shows by Release Year** – displays the release-year trend.
4. **Movies vs. TV Shows by Rating** – compares the content types across audience-rating categories.

The workbook also contains four PivotTables in the consolidated analysis sheet and slicer components for interactive filtering.

## Key Findings

- Movies account for approximately **69.7%** of the catalogue, while TV Shows account for approximately **30.3%**.
- The dataset contains **8,790 titles** in total.
- **TV-MA** is the most common audience rating, with **3,205 titles**.
- **TV-14** is the second most common rating, with **2,157 titles**.
- The release-year distribution shows a substantial concentration of titles released during the 2010s and early 2020s. The highest year in the consolidated release-year table is **2018, with 1,146 titles**.
- Country analysis provides a comparative view of the countries associated with titles. A title may be associated with more than one country, so country counts are country-title associations rather than mutually exclusive title totals.

## The Three Basic Data Analyst Questions

### 1. What did I analyze, and what question was I trying to answer?

I analyzed Netflix catalogue data across four areas: content type, country representation, release year, and audience rating. The main question was: **What does the Netflix catalogue look like across these dimensions, and what useful patterns can be identified to support business decisions?**

### 2. What specific findings did the analysis reveal?

The catalogue is made up of 6,126 Movies and 2,664 TV Shows, meaning Movies represent approximately 69.7% of the dataset. TV-MA is the largest audience-rating category, with 3,205 titles. The release-year summary has its highest count in 2018, with 1,146 titles. The dashboard brings these findings together with country representation and content-type comparisons.

### 3. What actions could the findings support?

The findings can support:
- Reviewing the balance between Movies and TV Shows.
- Exploring catalogue representation across countries and identifying areas for further market research.
- Using release-year patterns to understand the age profile of the catalogue.
- Reviewing the distribution of audience ratings when considering content classification and catalogue balance.
- Applying slicers to explore how these patterns differ across selected categories.

These are starting points for business investigation, not proof of audience demand or commercial performance.

## Strategic Recommendations

1. **Review the content mix:** Movies form the larger share of the catalogue. Decision-makers can assess whether this balance aligns with content strategy and audience objectives.
2. **Explore country representation:** Use the country analysis to identify markets for deeper research. Country counts should be interpreted carefully because one title can list multiple countries.
3. **Use release-year trends for catalogue planning:** Examine the distribution of older and newer releases when reviewing catalogue depth and content lifecycle.
4. **Consider rating balance:** The large number of TV-MA and TV-14 titles may inform further review of audience segments and content classification.
5. **Use interactive filtering:** Apply slicers to compare subsets of the catalogue rather than relying only on overall totals.

## Important Limitations

- The `release_year` field describes when a title was released, not when it was added to Netflix. It should not be interpreted as Netflix's annual acquisition or addition rate.
- Country counts may include the same title under multiple countries.
- Catalogue counts alone do not measure views, popularity, audience preference, revenue, or profitability.
- The dashboard summarizes the available dataset and should be combined with performance data before making commercial decisions.

## Workbook Structure

- **Dataset** – source Netflix titles data.
- **Consolidated data** – PivotTable summaries used for the analysis and dashboard visuals.
- **Dashboard** – executive visual report with four charts and slicer components.

## Conclusion

This final task combines the earlier Excel analyses into one executive-style reporting view. By bringing content distribution, country representation, release-year trends, and audience ratings together, the dashboard demonstrates how data can be organized and communicated to support business discussions and further investigation.

---

**Project:** Netflix Data Analysis  
**Task:** 6 – Executive Netflix Analytics Dashboard  
**Analyst:** Pearl Otimanam
