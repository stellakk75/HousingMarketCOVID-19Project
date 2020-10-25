# project-one
Project Phase started for GT analytic boot camp

Folders --> Files
1. RawData (unchanged raw data)
    - HomePriceFull.csv (Zillow)
    - pop2019.csv (Census)
    - pop2020.csv (Census)
    - Rental_price.csv (Zillow)
2. CleanedData
    - cleanup.ipynb (pulled 3 years of population, housing, and rental data into csv files below)
    	- cleaned_population.csv 
    	- cleaned_housing_rate.csv (all 3 years)  
	- cleaned_housing2018.csv, cleaned_housing2019.csv, cleaned_housing2020.csv (separate by years)
    	- cleaned_rental (pulled 2018-2020 rental information and only cities in common with population data)  
3. PopRelated (analysis related to Question 1)
    - HeatMaps.ipynb (coding gmap heatmaps for population 2018-2020 with cities with positive rate comparison changes only- increase in demand cities )
    - Q1PopulationAnalysis.ipynb (calculate yearly average, change in rate per year, change in rate per period 2018-2020)
        - pulled top 20 and bottom 20 based on the change rate 2018-2020 
        - exported to TopBotton folder (TopBottom/mostchangedpop or leastchangedpop)
    - sorted_population_final.csv = exported calculations from Q1populationanalysis.ipynb
    - Q1Populationanalysis_graphs.ipynb
        - Created all bar graphs for analysis 
4. QuestionAnalysis 
    -ChangingRates(Pop,Housing,Rental) (combined population, rental, housing data into one dataframe for common cities in all cleaned/analyzed data)(ChangingRates.csv)
    - HousingAnalysis.ipynb
        - calculate yearly average
        - top and bottom 20 cities for each year 
        - top 20 and bottom 20 cities for each year exported to csv files (Yearly Average of Top/Bottom 20 in 2018/2019/2020.csv)
        - Calculated overall difference in period 2018-2020 (housing_rate.csv)

    - Q2_barchartcomparison.ipynb 
	- Creates bar charts for housing rate 2018-2019 and 2019-2020 comparisons
    - Q2_housing.ipynb (needs to be rebuilt)
	- Create monthly trendlines for specific cities Atlanta, Boston, Vegas, NYC
    - Q3_popvhousing.ipynb 
	- Plots scatter plots comparing change in population vs change in housing rates and shows regression lines 

    - RentalAnalysis.ipynb
        -calculate yearly average and changing rate from 2018-2020 (rental_rate.csv)
    - Q4_rental.ipynb
        - Plot monthly rent prices for Atlanta for 2019-2020, 2018-2020 
        - Plot monthly rent prices for Boston for 2019-2020, 2018-2020 
    - ChangingRates.csv
    - housing_rate.csv
    - rental_rate.csv 

5. TopBottom
    - leastchangedpop18-19.csv
    - leastchangedpop19-20.csv
    - leastratechange18-20.csv
    - mostchangedpop18-19.csv
    - mostchangedpop19-20.csv
    - mostratechange18-20.csv
