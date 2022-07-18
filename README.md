# IronHack_ProjectOne
The great shark attack analysis

For this project The goal has been to create an analysis that determines during what month of the year what activity is the most dangerous. 
Besides how dangerous it is I also wanted to determine during which month that activity is the cause for most fatalities. 

First I started analysing the data set to determine what colums I wanted to use for the analysis and what needed to be cleaned to do so. 

I decided that I wanted to drop href', 'href formula', 'pdf', 'Unnamed: 22', 'Unnamed: 23'.

I create a new_Date to store new values as 12-april-2022 (dd-month-yyyy format)

Fatal (Y/N) also needed to be cleaned to only keep Y,N and "UNKNOWN" values 

'Case Number', 'Year', 'Country', 'Activity', 'Fatal (Y/N)' were selected as values to do the analysis with

The number of activities is too large and needs to be reduced to les optional values. 

- water sports (on top of the water)
- underwater sports
- Surfing (keeps its own value as it is such a large value)
- Swimming 
- Accidents 
- Wading in the water (standing)

Time to visualise the clean code

The first plot shows how the number of shark attacks has increased over the last 120 years. 
<img width="561" alt="first_plot" src="https://user-images.githubusercontent.com/104360125/179580586-92de8b46-8c79-4149-9c2b-2fbe16583dae.png">
#There is a steep increase during the last 40/50 years (this is probably because after the 2nd WW people started to have more free time and  the middle class started to grow

The second plot shows the activities that people used to part take in when they were targeted by sharks. We only look at the last 70 years as this is where the change is more visible

<img width="568" alt="second_plot" src="https://user-images.githubusercontent.com/104360125/179580624-fbcfa2e1-8092-42ba-b16b-29ca75525ee0.png">

In the thrird image we see the an even more specific plot of the last 20 years and see the activity changes per year both swimming and surfing have always seen a steady increase in nubers over the years 

<img width="550" alt="third_plot" src="https://user-images.githubusercontent.com/104360125/179580646-d631bcad-5b7d-4ce2-bb18-2bde68820e43.png">


In the fourth image we can see even more clearly how much larger the number of shark attacks on surfers is compared to swimmers 

<img width="562" alt="fourth_plot" src="https://user-images.githubusercontent.com/104360125/179580663-c09e6f53-575b-42d5-9efa-c9841707d2b2.png">

Besides the annual change I also wanted to show during what month of the year the majority of the attakcs take place. (July)

<img width="557" alt="fifth plot" src="https://user-images.githubusercontent.com/104360125/179580686-e26e32ef-b9ec-4846-b823-7569f0e0c4c2.png">

In this graph we can see out of the shark attacks how many at Fatal and non Fatal. It is clear to see that although surfers are the main target of sharks they are also the ones that percentage wise have a bigger chance of surviving the attack

The reason for surfers to survive more attacks is probably because they have a flotation devide and sharks must oftenly attact the oard instead of the person. 
people that are fishing, wading and doing underwater sports tend to have a small cgance of survival. 

The only group with even less survivors (relatively) are people that are in accidents, due to the accident they might already be incapacitated or be far off shore in deep waters where a rescue can be difficualt and dangerous

<img width="557" alt="sixth_plot" src="https://user-images.githubusercontent.com/104360125/179580708-60956f96-134d-4423-bf47-fb674fb65c3a.png">

In the final graph we can see that the majority of fatal attacks take place in July, this is probably becasue this is a vacation month for many people. 

![last_plot](https://user-images.githubusercontent.com/104360125/179580725-4a98840a-3648-4515-8e18-04bb6ce2f714.png)
