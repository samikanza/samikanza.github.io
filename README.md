# disaster

This is our disaster management flooding app prototype, and it has the following folders:

- public_html 
	- contains the web application that we made, opening index.html will display the web application.

- python_code
	- The code behind our project is in the python_code folder which contains our python code that contains the english and chinese algorithms to detect flooding articles with the english and chinese dictionaries, and python scripts to create the data and json for our web application. 
	- chinese_part - the chinese algorithms to detect flooding
	- chinese_stopwords.txt - the chinese dictionary of flooding terms
	- create_json - folder of python scripts to create json for our web application and the matrix.csv for our visualisations
	- FloodTerms_filtered_35083.txt - the english dictionary of flooding terms
	- location_extraction - python script to extract location information from articles
	- news_source_files - the english news datasets we used

- presentation
	- the slides we created as part of this project