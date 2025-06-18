# Metadata Overview
**Dataset 1: Global Burden of Disease Study (GBD 2021)**

*Citation:* Global Burden of Disease Collaborative Network. GBD 2021 Results. Seattle, WA: IHME, 2022. Available from https://vizhub.healthdata.org/gbd-results/

**Metadata:**

*Variables:*

* location (country)
* cause (e.g. anxiety, depression)
* measure_name (Prevalence)
* val (absolute burden)
* year

*Structure:* Long-format panel data; each row = country-cause-year combo

*Timeframe:* Includes historical time series from 2012.

*Unit of observation:* Country-year-cause.

### Multi-source datasets: World Bank & World Population Review–Compiled Dataset (Merged Socioeconomic Indicators)

**Sources:**
- World Bank. (n.d.). *World Development Indicators (WDI)* – GDP per capita, urbanization, population. [World Bank WDI](https://databank.worldbank.org/source/world-development-indicators)  
- World Bank. (n.d.). *Poverty and Inequality Platform: Gini index*. [Gini Index – PIP](http://pip.worldbank.org)  
- World Bank. (n.d.). *Income share held by highest 10% (SI.DST.10TH.10)*. [Top 10% Income Share](https://data.worldbank.org/indicator/SI.DST.10TH.10?end=2023&start=2023&view=bar)  
- Gapminder. (n.d.). *Population data documentation (GD003)*. [Gapminder Population](https://www.gapminder.org/data/documentation/gd003/)
- World Bank. (n.d.). *The world by income and region*. [World by Income and Region](https://datatopics.worldbank.org/world-development-indicators/the-world-by-income-and-region.html)
- OECD. (n.d.). *Gini index – disposable income*. [OECD Gini Index](https://data-explorer.oecd.org/vis?fs[0]=Topic%2C1%7CSociety%23SOC%23%7CInequality%23SOC_INE%23)

**Metadata:**

- **Structure:** Cross-sectional dataset using the latest available year per country (from 2012).
- **Units:** Mixed units including percentages, index scores, and GDP in USD.  

**Variables:**

- **Inequality:**
  - `gini_index` – Gini coefficient of income inequality
  - `wealth_share_10` – Share of income held by the top 10%
- **Economic:**
  - `gdp_per_capita` – GDP per capita (USD)
  - `income_grp` – World Bank income group classification
