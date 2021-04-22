# Chemical_Dependence_Admissions
 This project explores Admissions data from [OASAS](https://data.ny.gov/Human-Services/Chemical-Dependence-Treatment-Program-Admissions-B/ngbt-9rwf) from 2007 to 2018 about chemical dependence treatment programs in the state of New York. Using Facebook's Prophet, I forecast future admissions for these programs. 

New York State's Office of Addiction Services and Supports ([OASAS](https://oasas.ny.gov/)) oversees one of the nation’s largest Substance Use Disorder systems of care with approximately 1,700 prevention, treatment, and recovery programs serving over 680,000 individuals per year. By analysing data from these programs, we can see if the program has been effective over the past decade. We can also use this data to predict what the future may hold for OASAS to adjust strategies for treatment and prevention.

To see some interesting visualizations, check out my [Tableau](https://public.tableau.com/profile/rachel.khoo#!/vizhome/ChemicalDependenceTreatmentAdmissions/11YearComparison-Substances) public profile.


![Choropleth Map of New York State by county](https://github.com/rhkhoo/Chemical_Dependence_Admissions/blob/main/Images/compare.PNG)

![Top 5 Counties Change since 2007](https://github.com/rhkhoo/Chemical_Dependence_Admissions/blob/main/Images/counties.PNG)

Putnam, Schedectady, New York, Sullivan, and Albany county have the highest overall admissions proportional to county population. New York County is the wealthiest county, followed by Putnam (4th overall), Albany (10th), Schenectady (17th), and Sullivan (36th) based on [per capita income]('https://en.wikipedia.org/wiki/List_of_New_York_locations_by_per_capita_income'). Since 2007, the number of admissions compared to Putnam's population has nearly doubled.

![Line graph showing how admissions per substance have changed](https://github.com/rhkhoo/Chemical_Dependence_Admissions/blob/main/Images/ads-by-substance.PNG)

There has been a decrease in admissions due to alcohol, though there was a slight uptick from 2017 to 2018. Admissions due to marijuana have decreased, possibly due to the drug's increasing legalization. Heroin experienced the greatest increase of all other substances, particularly starting in 2012. In 2011, a [new commissioner](https://oasas.ny.gov/commissioner-biography) of the OASAS was appointed, and some changes that occured in subsequent years could be attributed to programs she instituted. The Statewide Task Force to Combat Heroin and the Prescription Opioid Crisis was established 2016, and the number of admissions due to heroin and other opioids did decrease, suggesting this program is effective.  

![Line graph showing how admissions per substance have changed](https://github.com/rhkhoo/Chemical_Dependence_Admissions/blob/main/Images/under18substances.PNG)

For children under 18, marijuana is by far the substance for which patients are seeking dependence treatment the most, followed by alcohol. Admissions for people 55 and older have increased across all substance groups, with alcohol being the higest, followed by heroin. Admissions for 25-34 year-olds dependent on heroin saw a huge increase from 2011 to 2016. The overall national opiod dispensing rate peaked in [2012]('https://www.cdc.gov/drugoverdose/maps/rxrate-maps.html')</sup>, and perhaps addicts turned to illegal substitutes after the dispensing rates declined in subsequent years.

Over the past decade, overall admissions for chemical dependence are down.  There was a peak in 2009, possibly a delayed effect of the 2008 financial crisis. It is important to note, however, that just because admissions for treatment of chemical dependence have decrease, it does not necessarily indicate that the prevalence of chemical dependence has decreased, just that not as many people are seeking treatment.

Using Facebook's Prophet, I predicted the number of admissions for the next eight years.

![Line graph showing how admissions per substance have changed](https://github.com/rhkhoo/Chemical_Dependence_Admissions/blob/main/Images/forecast.PNG)


Overall admissions are expected to decline over the next decade, with periodic spikes that may follow changes in the economy. However, admissions for people between the ages of 25 to 34 are expected to increase, primarily due to heroin and other opiods. People under age 25 are expected to be admitted much less frequently, possibly because of the effectiveness of OASAS's prevention programs. People over 55 are expected to be admitted more for every substance. These patients may be life-long users, so changing this trend may prove difficult. 

![Line graph showing how admissions per substance have changed](https://github.com/rhkhoo/Chemical_Dependence_Admissions/blob/main/Images/young-heroin.PNG)

It is encouraging to see that overall, admissions for chemical dependence are on the decline. OASAS may want to target older patients and young opioid addicts to address the predicted increase in admissions. 
