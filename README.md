# Kickstarting with Excel

## Overview of Project

The project call Kickstarter data is a document in excel that contain information to help Louise with her project campaign. With the help of excel tools, the data is going to be organize and filter to generate insights in Louise project.

### Purpose

The purpose of the project it is to help Louis with her campaign for theater by using specific data such as the monetary goal, the blurb, the pledge, outcome, deadlines, categories, etc. Information that can help her know if that campaign would work or not. With the use of pivot tables and pivot chard, we are going to be able to analyze and visualize the deferments scenarios and the progress set to a graph.

## Analysis and Challenges

The analysis taken from louis’ campaign was understanding if it was possible or doable with the budget and the months the projection shows successful or failed.

The challenges going through the analysis of the campaign for Louis it was using new tools such as pivot tables, and the interpretation more in detail from the information in the pivot charts.

### Analysis of Outcomes Based on Launch Date
   
![table table fiels](https://user-images.githubusercontent.com/82455263/116332888-2e626500-a798-11eb-9ab4-04259b386b9b.png)
![data base outcomes based on launch date (2)](https://user-images.githubusercontent.com/82455263/116332910-34f0dc80-a798-11eb-9934-6845eb890739.png)

To analyze the outcomes based on launch date, it has to be filter specific information such as: parent category (Theater), years, outcomes, and the data based in the launch day and converted into date with the formula =(((J522/60)/60)/24)+DATE(1970,1,1). The launch code “1447174261” divided by 60 seconds, divided by 60 minutes and all divides by 24 hours, plus the year when Unix timestamp started the counting from.

### Analysis of Outcomes Based on Goals

![data base percentage outcomes-goals](https://user-images.githubusercontent.com/82455263/116332923-3c17ea80-a798-11eb-93db-f97121af6f3b.png)

 To analyze the outcomes based on goals, it must be built a table of goals with the number of success, failed and canceled project based on the monetary goal starting on UD$1,000 and with any amount greater than US$50,000 based on the category plays, the results show that there is a high amount of success campaigns income goals a small percentage for failed campaigns. 

### Challenges and Difficulties Encountered

I struggle with the command: COUNTIFS and selecting the right data in the right order, also the fact I must do it one by one, I tried to check for a conditional to run over “successful, failed and canceled” but I did not find anything helpful.

## Results

The first conclusion will be that the best months to launch are in May, June, and July. I came with this conclusion because looking at this result show that those are the months that are the most successful. Also, the months that are the less desirable to launch may be October, November, and December because they are the highest amount to fail. October has the most fails but December was the least successful. Because looking at the chart you can see that October has the highest fail outcomes (yellow line) but it not was the least successful.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/82455263/116332958-4803ac80-a798-11eb-9e20-07fc25407818.png)

The second conclusion will be that the 36 percent of campaigns are likely to fail when started, I found this calculation by getting the total number of fail campaigns and dividing by the total of campaigns and multiply by 100.The 61 percent of campaigns are likely to success when started, I found this calculation by getting the total number of success campaigns and dividing by the total of campaigns and multiply by 100.   

![data base outcomes based on launch date](https://user-images.githubusercontent.com/82455263/116332976-4fc35100-a798-11eb-93f6-5e3ac14b6c1e.png)

- What can you conclude about the Outcomes based on Goals?
![outcomes based on goals](https://user-images.githubusercontent.com/82455263/116333004-5b167c80-a798-11eb-9bc9-2ad3c5809d5b.png)

In the graph its can be analyzed that the percentage of successful are correlative like the percentage of failed campaigns. Which could mean the theater shows for “plays” are unlikely to work.

- What are some limitations of this dataset?

It would help more if the project count with extra information about online marketing, focus of ages and specific targets, also a subcategory with geographic specifications.

- What are some other possible tables and/or graphs that we could create?

Possibly a Pie chart would help with the geographic subcategory to decide the city where to launch.
A Tree chart would help with decision making by organizing into optimistic and pessimistic scenarios. 
Finally line chart with markers 
 
 ![data base percentage outcomes-goals](https://user-images.githubusercontent.com/82455263/116333025-65d11180-a798-11eb-82cf-88e3a9579054.png)
![graphic bases on percentage](https://user-images.githubusercontent.com/82455263/116333039-6e294c80-a798-11eb-9a75-5ad924975597.png)

