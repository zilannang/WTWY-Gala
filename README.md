# Exploratory Data Analysis (EDA) Projects of MTA Turnstile Data:

This repo contains Project data and solution at Istanbul Data Science Academy. Project is about Exploratory Data Analysis of Metropolitan Transportation Authority (MTA) Turnstile Data.


## Exploratory Data Analysis (EDA):

Exploratory Data Analysis, is an approach to analysing data set to summarise their main characteristic, often with visual methods. 

## Objective and Goal:

  Optimizing street crews to subway stations to sell tickets to the women-only premiere of WomenTechWomenYes(WTWY) in New York in Spring 2022

* Finding the busiest stations in general.
* Find the day with the highest traffic.
* Find the time zone of the day with the highest traffic.
* Find the most female-dominated neighborhoods in NYC.
* Finding the districts with high annual income per capita.

Then generate a result with this data.
 
## MTA Turnstile Data:

The MTA network comprises the nation’s largest bus fleet and more subway and commuter rail cars than all other U.S. transit systems combined. The MTA's operating agencies are MTA New York City Transit, MTA Bus, Long Island Rail Road, Metro-North Railroad, and MTA Bridges and Tunnels.

Data obtained from [MTA DATASET](http://web.mta.info/developers/turnstile.html)

### Field Description:

| Field Name |Description  |
|--|--|
  | C/A | Control Area (A002)  |
  | UNIT  | Remote Unit for a station (R051)  |
  | SCP |Subunit Channel Position represents an specific address for a device (02-00-00)  |
  | STATION |Represents the station name the device is located at  |
  | LINENAME|Represents all train lines that can be boarded at this station  |
  | DIVISION |Represents the Line originally the station belonged to BMT, IRT, or IND  |
  | DATE  |Represents the date (MM-DD-YY)  |
  | TIME | Represents the time (hh:mm:ss) for a scheduled audit event  |
  | DESC  |Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours)  |
  | Field  | Description |


| TIME | Represents the time (hh:mm:ss) for a scheduled audit event 

| DESC |

| ENTRIES | The comulative entry register value for a device |

| EXITS | The cumulative exit register value for a device |

## NYC Census Data:

The dataset is taken from Kaggle. Data obtained from [Census Dataset](https://www.kaggle.com/muonneutrino/mapping-new-york-city-census-data/data?select=nyc_census_tracts.csv)

### Field Description:

There are many fields. When we delete the ones we will not use, the following fields remain.

| Field Name |Description  |
|--|--|
| Borough | Districts in New York |
| TotalPop | Total Population of Districts |
| Men | Districts in New York |
| Women | Districts in New York |
| Income | Monthly Per Capita Income |
| IncomePerCap | Annual Per Capita Income |

