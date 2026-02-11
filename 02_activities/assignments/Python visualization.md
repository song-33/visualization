### Python visualization

* What software did you use to create your data visualization?
  * I used Python with the matplotlib library to create the COVID-19 visualization. Data source: [https://open.toronto.ca/dataset/monthly-communicable-disease-surveillance-data/]
* Who is your intended audience? 
  * My intended audience is the general public of Toronto and potentially public health officials/epidemiologists. This is of a presentation purpose to allow the broad audience to understand the trajectory of the pandemic within Toronto.
* What information or message are you trying to convey with your visualization? 
  * I want to show the trend and pattern of the pandemic over time, and identify several waves of outbreaks and the eventual decline in cases. This plot focuses on the change over time relationship.
* What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
  * I chose to present the data with a bar plot because it is the most straightforward way to show Time vs Cases changes. I used the standard 2D image with clean layouts, horizontal and vertical gridlines, to ensure the data was presented in an objective and factual way. In terms of axes, I used standard chronological order, and plotted with an interval of 3 (x axis label shown every three months) to ensure clarity and readability.
* How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
  * I ensured reproducibility by writing a script that processes raw data and generates the plot without using any random processes, so anyone with the data and code can get the same result. I specified the color and width of the bars, so the style was determined and would remain unchanged.
* How did you ensure that your data visualization is accessible?  
  * I used indigo bars against a white background, providing high contrast to make the plot easily distinguishable. I chose the default sans-serif font with at least a font size of 12 to ensure texts are more accessible.
  * I could add alt-text to describe the plot so that it is fully accessible to screen readers: "A line graph showing COVID-19 cases in Toronto surging in late 2020 and early 2022, and declining by 2024."
* Who are the individuals and communities who might be impacted by your visualization?  
  * Residents of Toronto will likely be impacted, especially vulnerable communities who can rely on this data to make informed risk assessments. Also, healthcare workers and public health officials can be impacted to make more informed decision in the future. 
* How did you choose which features of your chosen dataset to include or exclude from your visualization? 
  * I chose to present the Time vs Cases temporal relationship, so I selected the number of cases per month to achieve this goal. I only wanted to present the COVID data, so I excluded data of all the other communicable diseases. I also excluded the YTD (Year-to-Date) columns because they were irrelevant to my plot and would obscure the month-to-month variation I wanted to show. It is important to note that only the infection numbers were shown, but not the demographic details, or outcome severities (these are not available in the dataset), so there are unseen data that are not included in the visualization as well.
* What ‘underwater labour’ contributed to your final data visualization product?
  * The underwater labour includes many aspects, such as data collection (the public health workers and hospital staff who conducted tests and reported case data), infrastructure (the City of Toronto IT support team who maintains the Open Portal database), and data preprocessing (me extracting and consolidating data from database files of consecutive years).