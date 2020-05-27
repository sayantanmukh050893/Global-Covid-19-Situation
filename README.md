## Global Impact of Covid-19

In the following blog we would analyse the global covid-19 data from different countries and come to a conclusion about the overall condition of the each country in fighting with the covid-19 situation.

### Source

The data used for the analysis of Global Impact of Covid-19 is taken from the following website :-
https://www.worldometers.info/coronavirus/

This website contains the following information related to Covid-19 for each and every countries :-

- Total Cases
- New Cases
- Total Deaths
- New Deaths
- Total Recovered
- Active Cases
- Serious, Critical
- Tot Cases/ 1M pop
- Deaths/ 1M pop
- Total Tests
- Tests/ 1M pop
- Population

### Procedure

This website is scrapped on a regular basis and then all these informations are retrieved. Further data cleaning and adta transformation takes place on these data.

Based on all the data, four parameters are calculated primarily for every country :-

- Active Cases Rate
- Total Tests Rate
- Total Recovered Rate
- Mortality Rate

Then four new categorical features are introduced for every country based on the following rules :-

1. Active Cases Condition :- 
- Good :- Active Case Rate lies within 50th percentile of the global active case rate
- Medium :- Active Case Rate lies between 50th and 75th percentile of the global active case rate
- Bad :- Active Case Rate lies between 75th and 100th percentile of the global active case rate

2. Total Test Condition :- 
- Good :- Total Test Rate lies between 75th and 100th percentile of the global active case rate
- Medium :- Total Test Rate lies between 50th and 75th percentile of the global active case rate
- Bad :- Total Test Rate lies within 50th percentile of the global active case rate

3. Total Recovered Condition :-
- Good :- Total Recovered Rate lies between 75th and 100th percentile of the global active case rate
- Medium :- Total Recovered Rate lies between 50th and 75th percentile of the global active case rate
- Bad :- Total Recovered Rate lies within 50th percentile of the global active case rate

4. Mortality Condition :-
- Good :- Active Case Rate lies within 50th percentile of the global active case rate
- Medium :- Active Case Rate lies between 50th and 75th percentile of the global active case rate
- Bad :- Active Case Rate lies between 75th and 100th percentile of the global active case rate

These 4 conditions further helps us to decide upon an Overall Condition which categorises a country as either Good, Medium or Bad based upon the countries performance in fighting Covid-19.

The data thus formed is then fed into Google Data Studio and a Dashboard depicting all these features are shown.

### Dashboard Link :- https://datastudio.google.com/reporting/1f332cf3-9621-41a1-a119-0c8121e68767/page/BNYQ
