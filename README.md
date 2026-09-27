# Monthly U.S. Domestic Airline Passengers

**Nihar Shah — Business Forecasting**

## 1. Data file

The file [`us_domestic_airline_enplanements_monthly.csv`](us_domestic_airline_enplanements_monthly.csv) contains monthly passenger boardings on scheduled domestic flights operated by U.S. airlines. It covers **January 2000 through May 2026**. The data come from the U.S. Bureau of Transportation Statistics (BTS) and were downloaded from [FRED (series ENPLANED)](https://fred.stlouisfed.org/series/ENPLANED) on September 27, 2026. The numbers are **not seasonally adjusted**, so seasonal travel patterns are visible.

## 2. Description of the data (data dictionary)

Each row represents one month. An **enplanement** means a passenger boarding a plane. Someone who boards two flights is counted twice; this is a count of boardings, not unique people.

| Column | Description | Format or unit | Example |
| --- | --- | --- | --- |
| `observation_date` | Month when the boardings occurred; shown as the first day of that month. | `YYYY-MM-DD` | `2026-05-01` means May 2026 |
| `ENPLANED` | Number of boardings on scheduled U.S. domestic airline flights. | **Thousands of boardings** | `73760` means about 73.76 million boardings |

There are 317 monthly observations and no blank values in this CSV. The file does not include international flights. It ends in May 2026 because that was the latest month available in this series when downloaded.

## 3. Data collection methodology

U.S. airlines report their passenger traffic **every month** to BTS, part of the U.S. Department of Transportation, using Form T-100. BTS compiles and publishes the airline data. FRED makes this BTS series available as a downloadable CSV. Published values may later be revised. [BTS explanation of the T-100 data](https://www.transtats.bts.gov/DatabaseInfo.asp?QO_VQ=EED)

## 4. Why this dataset intrigues me

I am interested in planes and air travel. I want to see how passenger boardings change during busy travel seasons and how events such as the COVID-19 pandemic affected flying. Because the data are monthly and cover many years, I can use them to practice forecasting future passenger demand.
