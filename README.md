# Key economic figures for the 54 African countries

A clean, ready-to-use table of 13 key indicators for every African country, each with its year and its World Bank source code. It is useful for market sizing, country analysis, case interview practice, class projects and quick comparisons between countries.

Snapshot of 14 November 2026. Country names are given in English and in French.

## Files

| File | Shape | Use it for |
|---|---|---|
| `africa-54-countries-key-figures-long.csv` | 652 rows, one per country and indicator | Filtering, joining, charts by indicator |
| `africa-54-countries-key-figures-wide.csv` | 54 rows, one per country | Spreadsheets and quick comparisons |

## Indicators

| Indicator | World Bank code | Unit |
|---|---|---|
| Real GDP growth | NY.GDP.MKTP.KD.ZG | % per year |
| Inflation, consumer prices | FP.CPI.TOTL.ZG | % per year |
| GDP | NY.GDP.MKTP.CD | current US dollars |
| GDP per capita | NY.GDP.PCAP.CD | current US dollars |
| GDP per capita, PPP | NY.GDP.PCAP.PP.CD | current international dollars |
| Population | SP.POP.TOTL | people |
| Life expectancy at birth | SP.DYN.LE00.IN | years |
| Access to electricity | EG.ELC.ACCS.ZS | % of population |
| Internet users | IT.NET.USER.ZS | % of population |
| At least basic drinking water services | SH.H2O.BASW.ZS | % of population |
| Forest area | AG.LND.FRST.ZS | % of land area |
| Unemployment, modeled ILO estimate | SL.UEM.TOTL.ZS | % of labor force |
| Poverty headcount ratio at the international poverty line | SI.POV.DDAY | % of population |

## Columns (long file)

`iso3`, `country_en`, `country_fr`, `indicator`, `indicator_code`, `unit`, `value`, `year`, `latest_available_only`, `source`, `note`.

In the wide file, each indicator has a value column and a `_year` column.

## Good to know

- Each value is the latest one the World Bank had published for that country on 14 November 2026, so years differ between indicators and countries (2021 to 2025 here). Always quote the year with the figure.
- `latest_available_only = yes` marks a value that is older than the usual year for that indicator.
- An empty cell means the World Bank has no recent value for that country.
- Unemployment is a modeled estimate by the International Labour Organization, not a survey count.
- Poverty is only available for the countries with a recent household survey.
- Comoros: the figures cover Ngazidja, Ndzuwani and Mwali. Maoré (Mayotte), still under French colonial rule, is not counted by the World Bank: it had 323,153 inhabitants on 1 January 2026 (INSEE census).

## Source and license

Data: World Bank, World Development Indicators (https://data.worldbank.org), licensed under CC BY 4.0. Mayotte population: INSEE (https://www.insee.fr/fr/information/9022279).
This compilation is shared under CC BY 4.0. Please cite: "World Bank, World Development Indicators, compiled by Invea (Consulting 360), November 2026."

## About Consulting 360

This table comes from the country data used in Consulting 360, a mobile app by Invea (Paris, France) to master consulting, prepare case and fit interviews and work on African markets. The app has a profile for each of the 54 African countries with sourced indicators, maps, rankings and trends. It is free to download on iPhone (App Store) and Android (Google Play), with an optional Pro subscription.

- Website: https://consulting360.app/
- The 54 African countries, one page per country: https://consulting360.app/africa-countries.html
- iPhone: https://apps.apple.com/app/consulting-360/id6797010196
- Android: https://play.google.com/store/apps/details?id=org.invea.consulting360
