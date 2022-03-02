# test_projects
data projects
We start with importing the required libraries
Requests, bs4,BeautifulSoup, csv, html5lib, pandas.
We are using IMDB’s website for this trial data is tabular format
https://www.imdb.com/chart/top/
<img width="529" alt="1" src="https://user-images.githubusercontent.com/97940840/156174441-c9b472af-1151-4a41-afd8-dec7e8f12775.png">

Lets parse the website to make it usable using html5lib parser
<img width="669" alt="2" src="https://user-images.githubusercontent.com/97940840/156174579-e6a2ec6b-2251-45b8-88da-577c475f7d16.png">

Lets find where the data values are.
<img width="665" alt="3" src="https://user-images.githubusercontent.com/97940840/156174637-0893125a-f4e7-4fae-97e6-3d5f1f49b785.png">

Lets find where movie names are with below code.
<img width="374" alt="4" src="https://user-images.githubusercontent.com/97940840/156174847-e2831d6a-15b9-4a1b-8571-c9135cc373cf.png">

Lets find where movie years are with below code.
<img width="484" alt="5" src="https://user-images.githubusercontent.com/97940840/156175112-e8ccbf60-feb3-4480-8f3e-ea671e88dc7c.png">

Now as we can access the individual components lets make  a loop to fetch all data and replace non-existent values as None. Printing Movie Names.
<img width="635" alt="6" src="https://user-images.githubusercontent.com/97940840/156175176-9ceb1220-1386-4779-84cb-18281936be04.png">

Now Printing Ratings column.
<img width="631" alt="7" src="https://user-images.githubusercontent.com/97940840/156175239-2a519179-c46d-4783-8f87-e68916b2fe9c.png">

Now lets create a dataframe to see all this.
<img width="274" alt="8" src="https://user-images.githubusercontent.com/97940840/156175294-d65fc2d9-1402-4239-abdc-221f9dfb5edf.png">

Now lest save the file as csv with below code for later use.
<img width="338" alt="9" src="https://user-images.githubusercontent.com/97940840/156175381-e395f25b-dc90-4b9c-b573-84575a316e64.png">

<img width="313" alt="10" src="https://user-images.githubusercontent.com/97940840/156175437-fea2b906-649a-4405-939e-4f247ae234b3.png">
Data saved !
