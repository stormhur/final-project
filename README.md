<text align="center"> <h1> Storm Hurwitz Final Project </h1>
<h2> Web Coding for Interactive Design </h2>
<h2> Project Title: New York City's HIV/AIDS Faith-based Initiative </h2></center>

<h3>Project Link: http://stormhur.github.io/final-project/ </h3>
<br>
#<h3> Description </h3> 

New York City Department of Mental Health and Hygiene is quite progressive in its funding of Faith-based Organizations (FBOs) to do HIV/AIDS prevention and support work. Of course, hearing this might raise the question, why?

The target population of most HIV/AIDS prevention work is young black men who have sex with men (MSM) because this demographic is at the highest risk of contract HIV/AIDS. At the same time, persons of African descent in the United States of America are exponentially more likely to be religiously devout. Because faith is typically seen as something against queer sexual relations and, in some instances, any form of sex prior to marriage in general, it is often attributed to being a major factor in the transmission of HIV/AIDS. The more stigma, the less an individual is to get tested, practice safe sex, or seek and abide by medical help should they test positive. 

While interning at GMHC (formerly known as Gay Men's Health Crisis) during the winter and spring of 2015, I conducted interviews and research on this policy intersection. I became fascinated with the importance of this contentious intersection. Was it important to persons living with HIV/AIDS (PLWHA) in NYC? What organizations were being funded? Where were they located?

While working at GMHC, I originally proposed to create a map that would juxtapose the NYC funding of FBOs on top of a map depicting the percent of PLWHA in each Community District of Manhattan. However, I did not have the skillset to create the map and, quite honestly, the conversation on the intersection had not been written about much up until that point. So, instead, I interviewed several GMHC clients, all of which were PLWHA, and wrote an article, which was published in *POZ Magazine*, on the importance of these funding efforts. [Click here to read the full article](http://www.poz.com/articles/faith_based_communities_2959_27430.shtml). 

Now, having completed most of Web Coding for Interactive Design at The New School, I am prepared to generate the map that I originally wanted to create that can be presented alongside the article I wrote. The purpose of creating this map is that individuals can see whether the FBOs being funded during the Fiscal Year (FY) 2014 were located in areas where there is a higher population of PLWHA. Further, it enables the user to easily comprehend the amount of FBOs funded, their religious affiliation, location, and amount funded during FY2014. 

<h3> Project Procedure </h3>
Because my new project is interested at creating a visualization of spatially where New York City Department of Mental Health and Hygiene's HIV/AIDS Faith Based Prevention Initiative Funding is being allocated towards, I had to do quite a lot of work to generate this map. In order for the user to determine the effectiveness of the funding, I found it necessary to visualize where there is the highest density of Persons Living with HIV/AIDS (PLWHA) in Manhattan, New York. I did this through generating a chloropleth map of the prevalence of PLWHA in each Community District (CD). An initial challenge in data cleaning on this end that I faced was that the NYC Surveillance Data on PLWHA is separated into zones as determined by Ryan White policy, whereas I have only been able to find polygon shapes for CDs. However, I was able to solve this issue quite easily because the zip codes easily separated from the Ryan White districts into the CDs.

Then, I found the dataset regarding what faith-based organizations (FBOs) were funded during the Fiscal Year (FY)2014. I took this data and cleaned it so that only FBOs in Manhattan were represented. I then went through and found the longitude and latitude, religious affiliation, and funding amount associated with each FBO. I uploaded this cleaned dataset into CartoDB and added it to the CD map as a second layer. I then chose to create a bubble map out of the FBO locations. I chose to do this because the bubbles adjust in size depending upon the amount of funds they received during FY 2014. Then, in order to add more depth to also determine what religious affiliations were most funded, I generated CSS code that changed the colors of the bubbles on the map depending upon the religious affiliation of the FBO. In order to create a Legend for this information, I edited the HTML in CartoDB of the Legend information for bubble maps to instead match that of categorical dot maps.

I then created a scroll feature using JavaScript for the bubbles that informs the user of what the title of the FBO is, the religious affiliation, and the amount funded. After that, I created a click feature using Javascript for the CDs that informs the user of what CD they are looking at and the percentage of the population that is PLWHA.

In order to make sure that my work is readable by all communities as well as aesthetically pleasing, I used ColorBrewer and Flat UI Colors to generate my color palette. I worked with JavaScript, HTML, and CSS in order to complete my project. You can see the finished project by [clicking here](http://bit.ly/1WNEBdg)!

<h3> Images </h3>

![CartoDB Stormhur](http://i.imgur.com/rKsUHXj.png)

<h3> Sources </h3>

*Source for Graphic*: CartoDB, [CartoDB Stormhur](http://bit.ly/1WNEBdg)

Hurwitz, Storm. '[From Churches to Mosques: We Need to Include Every Faith Community in the Fight Against HIV.](http://www.poz.com/articles/faith_based_communities_2959_27430.shtml)' *Poz Magazine*, 2015. 



 



