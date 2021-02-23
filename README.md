# Bureau of Prisons COVID data

```
                     ________
M               M   /_  __/ /  ___
M M           M M    / / / _ \/ -_)
M M M       M M M   /_/_/_//_/\__/         __        ____
M M M M   M M M M     /  |/  /__ ________ / /  ___ _/ / /
M M M M M M M M M    / /|_/ / _ `/ __(_-</ _ \/ _ `/ / /
M M M M M M M M M   /_/__/_/\_,_/_/ /___/_//_/\_,_/_/_/
M M M M M M M M M     / _ \_______    (_)__ ____/ /_
M M M M M M M M M    / ___/ __/ _ \  / / -_) __/ __/
M M M M M M M M M   /_/  /_/  \___/_/ /\__/\__/\__/
                                 |___/

```

Since March, The Marshall Project has collected and published [weekly data](https://github.com/themarshallproject/COVID_prison_data) on [coronavirus in prisons across the country](https://www.themarshallproject.org/2020/05/01/a-state-by-state-look-at-coronavirus-in-prisons).

We collect the data aggregated for each system as a whole. But in the process, we also have vacuumed up data for individual facilities in some systems. Most notably, we've collected [the raw JSON data](https://www.bop.gov/coronavirus/json/final.json) behind the [Bureau of Prisons's COVID-19 dashboard](https://www.bop.gov/coronavirus/index.jsp) since the end of April. 

In the `snapshots` folder, you'll find one json file with the date it was collected embedded in the filename. We've grabbed the snapshot every time the JSON has changed from April 30, 2020 until Jan. 27, 2021. We're making this public in case it's useful for other coronavirus researchers. 

## Caveats
Note that the file `snapshot-2020-06-06T03:56:27-04:00.html` was a snapshot that failed and got a 403 error from the server. 

This is provided without warranty. We don't have documentation from the BOP for the meaning of these fields, though we have been told that to determine the total number of cases, one must add the current cases with the recovered cases and the deaths. 

We will not be maintaining or updating this data over time. It is simply a one-time series of snapshots.

## Questions and Bugs
If you have questions about the data, please email us at [info+covidtracker@themarshallproject.org](mailto:info+covidtracker@themarshallproject.org) or file a [Github issue](https://github.com/themarshallproject/COVID_prison_data/issues).