<h1>Table of Contents</h1>

<h4>1. Installation</h4>

<h4>2. Project Motivation</h4>

<h4>3. Data</h4>

<h4>4. File Description</h4>

<h4>5. Results</h4>

<h4>6. Licensing, Authors, and Acknowledgements</h4>

<h4>7. Author</h4>



<h2>Installation</h2>
I would recommend to download annoconda on your machiney.


<h2>Project Motivation</h2>
This is the Coursera Caption project. The goal of this project is to find the ideal location to build a new cinema in the USA. We found this by asking a few questions listed below.

<h4>1.Footfall of the location ?</h4>
<h4>2. Customer purchase behaviour ?</h4>

<h2>Tools Used and Data</h2>

Foursquare API

Jupyter Notebook on local machine /IBM Watson Account



Data

The Wikipedia page (https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population) was scraped using the BeautifulSoup library to build a pandas dataframe listing the cities, states, coordinates, area and population density. The dataframe was cleaned and processed appropriately.

The Wikipedia page (https://en.wikipedia.org/wiki/List_of_United_States_counties_by_per_capita_income) was scraped using the BeautifulSoup library to build a pandas dataframe listing the cities, states and percapita income. The dataframe was cleaned and processed appropriately.

The Foursquare API is then used to get the venues in each city of United States Based on the categories of each venue as decided by the CEO, we have assigned weights to each of them and got the city that has the maximum weight.

<h2>File Description</h2>

IntroductionBusiness Problem.pdf: Intros About Business Problem.

CAP.pdf, CAP.PPT: Depth Business Plan  and metholody involved in PDF and PPT format respectively

The battle of Neighbourhoods - Final Report.ipynb : The actual source code of data 

The battle of Neighbourhoods - Final Report.ipynb : Report and conclusion from the above data.

<h2>Result</h2>

Based on the given constraints, the green circle is ideal place to build the cinema for mass footfalls and revenue

<h2>Licensing</h2>

Big thanks to Coursera for this capstone project. I would also like to thank wikipedia for the data.

<h3>Author</h3>
Saphal Adhikari
https://www.linkedin.com/in/saphaladhikari/
https://medium.com/@franticarsenal





