# Overview

## Covid-19 Data Analysis¶
This notebook is used to understand the comprehension of Data Analysis techniques using Pandas library

### Data Source:
https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports

### File naming convention
MM-DD-YYYY.csv in UTC.

### Field description
Province_State: China - province name; US/Canada/Australia/ - city name, state/province name; Others - name of the event (e.g., "Diamond Princess" cruise ship); other countries - blank.

Country_Region: country/region name conforming to WHO (will be updated).

Last_Update: MM/DD/YYYY HH:mm (24 hour format, in UTC).

Confirmed: the number of confirmed cases. For Hubei Province: from Feb 13 (GMT +8), we report both clinically diagnosed and lab-confirmed cases. For lab-confirmed cases only (Before Feb 17), please refer to who_covid_19_situation_reports. For Italy, diagnosis standard might be changed since Feb 27 to "slow the growth of new case numbers." (Source)

Deaths: the number of deaths.

Recovered: the number of recovered cases.