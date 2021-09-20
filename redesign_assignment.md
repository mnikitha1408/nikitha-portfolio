# Critique by Design (Assignment 3 & 4)

## Step One: Finding a data visualization

I came across a very interesting chart on Statista that was depicting restaurant performance in the United States over the last decade.<br/>
I was driven to investigating it because the chart took a **single** relatively straightforward measurement (not commenting on how it is measured) and complicated it. <br/>
At first glance, I knew that it could be improved.<br/>
Here is the link to the chart,
https://www.statista.com/statistics/214747/us-restaurant-performance-index/

Here is a screenshot of it,

Some context that might be necessary,<br/>
The restuarant performance index measures the overall health of the US restaurant industry. The index is based on the results of a monthly survey that is composed of a variety of indicators including sales, traffic, labor and capital expenditures. A value above 100 signals a period of expansion while a value below 100 signals a period of contraction.


## Step Two: Critique
Using Stephen Few's *Data Visualization Effectiveness Profile*, I critiqued the chart on how informative and emotive it was. 
Identified potential audience - Food critics, bloggers, city council members etc. <br/>
**Usefulness:** I rated it low here because I felt that the chart would not be very useful to the identified audience. The only data point shown is a very broad measure, the performance index. We do not have any data on the different components that make up the index itself (like demographics, sales, capital expenditure etc.). <br/>
**Completeness:** It did not really contain all the information that was necessary to make it understandable. There was no context on what the restaurant performance index was and why the Y-axis started at 92.5<br/>
**Perceptability:** Although the chart did not make illogical comparisons, it is not easily perceptive. I had to spend time carefully going over the lines to understand that it was trying to show the difference through the years. Even the pop-up box (when scrolling over a data point) was not easy to understand.<br/>
**Truthfulness:** The chart does not misrepresent any data or make any comparisons that aren't correct.<br/>
**Intuitiveness:** I rated it very low on intuitiveness because I felt that the X-axis with the months was different. And the years were not arranged in any particular manner because it was showing the trend line and that made it more counterintuitive. <br/>
**Aesthetics:** I rated it low on aesthetics because there are too many colours on the chart. The legend is not helpful at all. I mistook the incomplete data for 2021 as the data for 2013 because both of them were very similar shades of grey. <br/>
**Engagement:** It was average on engagement because I felt like the audience would be compelled to try and make sense of the chart. 


### The Good Charts Method:
* At first glance: A lot of lines. Too many colours. One line that abruptly ends. 
* What worked: The font on the axes is pleasant. I like the grid lines (it is easy to associate with the Y-axis label values.)
* What didn’t work: The title is too long. The years are not on the X-axis (it is not intuitive). Associating each colour to the corresponding year is very confusing. Comparing the differences between the years is difficult. The chart is too congested (too many lines). 
* What I would do differently: I would first provide some context about what the restaurant performance index is. I would shorten the title. I would also highlight 2015 and 2020 to show the stark difference between them. 

## Step Three: Wireframing a solution

Having critiqued the chart, here are some thoughts/changes I thought to implement. 
* Focus on how the restaurant industry was affected in the US in 2020 as a result of the pandemic. 
* Reduce the number of colours on the chart.
* Compare 2020 (worst performance index) with the best performing year to highlight the difference. 
* Highlight the neutral performancce level of 100.
* Reduce clutter by getting rid of the legend as well as the labels for each year.
* Retain the type of chart to capture fluctuations through the months.

I created a wireframe to test it and this is how it turned out.
![Wireframe](/wireframe.jpeg)

## Step Four: Testing the solution

In order to check if the redesign I was proposing would actually make a difference, I showed my wireframe to two of my friends. I wanted their input and feedback on what they thought my chart represented, if it was conveying the message effectively etc.
I structured our conversation around the same four questions to help facilitate this. I also made sure I didn't provide any leading information since that would skew the feedback. Here is how it went,

**Person #1**:
Didn’t immediately pick up on the fact that the chart was about restaurant industry performance. (Title was not effective enough)
1. What do you think the chart is about?
  * Comparison between something in 2020 and 2015.
  * 2020 was not a good year for restaurants.
2. Who do you think is the intended audience for this?
  * Anyone who is interested in investing in restaurants or owns a restaurant. This will tell them how the industry is performing - to increase/decrease prices etc.
3. Is there anything you find confusing or surprising about the chart?
  * I don’t understand why a score of 92 is bad. (The y-axis)
  * The grey lines in the centre of the chart is adding clutter (confusing)
4. Any other comments?
  * Why is 2015 so high? 
  * The title is not clear (You are comparing months of different years but it says through the years?)

**Person #2:**
2020 Feb was not good for something. Thought it was a covid related chart.
1. What do you think the chart is about?
  * 2020 and 2015 comparison for restaurants
2. Who do you think is the intended audience?
  * Newspapers/articles? General public awareness of the effect of covid
3. Is there anything you find confusing or surprising about the chart?
  * The Y-axis label 2.5 units measure? 
  * Are the other years averaging out near the centre line? (Unclear, distracting)
4. Any other comments?
  * Maybe provide information about how to read the performance index. 
  * I would make the X-axis years and use the average performance of each year as the data so I can see trend over time.

### What I learnt from the feedback
* I should not highlight 2015 because it was taking attention away from 2020, on which I wanted to focus.
* Both of them felt that the title was not helpful. 
* Change the title to something that was simple and clear.
* Give some context about what the Restaurant Performance Index is.
* The index on the Y-acis was not making sense to them both.


## Step Five: My redesigned data visualization
<div class="flourish-embed flourish-chart" data-src="visualisation/7303916"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

