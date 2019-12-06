# Critique by Redesign
#### Page nav
<!-- AUTO-GENERATED-CONTENT:START (TOC:collapse=true&collapseText=Click to expand) -->
<details>
<summary>Click to expand</summary>
- [The original visualization](#the-original-visualization)
- [The critique process](#the-critique-process)
- [Portfolio](#portfolio)
  * [Final Project](#final-project)
  * [OECD Data Visualization](#oecd-data-visualization)
  * [Critique by Redesign](#critique-by-redesign)
  * [Some quick in-class exercises](#some-quick-in-class-exercises)
  </details>
<!-- AUTO-GENERATED-CONTENT:END -->

## The original visualization
For this assignment, I decided to critique Figure 1 from  
["Will a Five-Minute Discussion Change Your Mind? A Countrywide Experiment on Voter Choice in France"](https://www.hbs.edu/faculty/Publication%20Files/aer.20160524.compressed_421e1937-b6c3-46de-ab46-03c207264cf6.pdf) by Vincent Pons.

![Figure 1. Results of the 2012 and 2014 Elections](/figure1.png)

I selected this visualization because there is valuable information contained for readers of the paper that are pretty difficult to extract from the current design. I came across this visualization quite serendipitously. As my study buddy was doing reading for their econometrics course, I caught a glimpse out of the corner of my eye. Out of curiosity, I asked them to share the article with me, and as soon as I stumbled across this visualization, I wanted to tackle the challenge of making it tell a more clear story.


## The critique process
### Stephen Few's [Data Visualization Effectiveness Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf)

This is a great critique method for considering targeted audiences for visualizations. While many visualizations are, in the end, public because of our communication standards and forums in the digital age, the context of a visualization and the intended audience should hold priority. Few's Data Visualization Effectiveness Profile helped me note the busyness and lack of clarity, as well as some repeated information in the visualization. 

First, I wanted to address the issue of color because this is a paper discussing politics. In America, reds and blues represent the two parties when it comes to politics - right and left, respectively. For the French parties, these colors are switched. Thus, I felt I needed to derive my own color scheme to avoid confusion.

Through my redesign, I also wanted to remove repeated information, such as the keys/legends and repeated labeling. Rating the visualization on a scale of 1-10 for various attributes was also quite helpful to narrow my focus on areas to redesign.


### Wireframing
This was my wireframe for the redesign. I tried to simplify the labeling and voter turnout ratios for less visual clutter and chose a color scheme (ill-represented by my colored pencils) from ColorBrewer 2.0. 
![Redesign Wireframe](/IMG_20191110_220249.jpg)
Both of the "readers" I discussed this wireframe with had a struggle understanding the visualization at first, as they lacked context. I realized that I should make the title more clear - "French Elections Discussed in This Paper" - so that even if the visualization was taken out of context, it should be easier to discern the story being told. Additionally, I was given feedback about my legend, as PS and UMP were undefined. However, given the context of the paper and the added detail in the title, I would perhaps would not include a spelling out of what each of those acronyms represent. One person also recommend adding percent labels to the bars for more detailed and clearer data. Thankfully, the colors were not confusing, as I believe they could have been had I kept the original colors.


### Redesigning
I fell ill with a high fever and was subsequently unable to complete my redesign. However, the following is a verbal description of my final redesign, with key changes I would have made to my wireframe based on user feedback **_bolded_**:

_The final visualization is to be read top to bottom (**rotate wireframe** contents 90 degrees clockwise), with a **descriptive title** - "French Elections Discussed in this Paper." I had considered adding a subtitle describing the results of the experiment, but decided against it as this figure comes early on in the paper and is used to set the scene for the rest of the report. I decided to rotate the wireframe design to tell a more clear story since the paper discusses impacts of door-to-door canvassing on voter turnout and, subsequently, vote shares in the election. It is easier to compare the (average) voter turnout values reading horizontally left to right. These numbers would be presented in large, bold font with a small, gray text label on the left "Voter Turnout." Effectively, I want to redesign this figure as an infographic table, with the various elections as column headings._

_The second "row" would be the first round voter shares, depicted as horizontal stacked bars with **percentage labels** for clarity about proportions. The color scheme I would use would be similar to [this](http://colorbrewer2.org/?type=diverging&scheme=PuOr&n=7) scale from purple to orange-brown, as represented in my wireframe._

_The third and final row of the table is the results. I chose to maintain this order of rows for logical reading when using the standard top-down left-right of the U.S., where this paper was published. The results would generally be portrayed as they were in my wireframe. Originally, I had wanted them to all follow the same format. However, the sorts of data represented here are quite different, so I decided it was okay (given **no particular feedback** from my users) to present the results as such. The presidential election results would be displayed as a horizontal bar chart for more clear comparison. The parliamentary election results would still be displayed as a semi-pie (similar in shape to the room where the French Parliament meets), and the European elections results would be displayed as a unit chart to break any expectations of parallel structure between the results. Additionally, since those elections are for only 74 seats, it is easier to see the results in the unit visualization than for the 577 seats in Parliament._

_Overall, I decided not to reduce too much information from this visualization as I believe it is essential to building the reader's understanding of the discussion that follows it. However, I think my choices for redesign would make the visualization more readable and the data more clear for interpretation._

### Make-up Redesign
Final redesign done in Tableau but presented as an image here. I couldn't figure out labeling within a reasonable amount of time, but I would have included the "column" labels [2012 Presidential, 2012 Parliamentary, 2014 European] and average voter turnout, as well as "row" labels [First Round, Second Round], as discussed above. Additionally, I could not figure out how to rotate the semi-pie or get the unit visualization to work, so those elements are unfinished as well. Still learning Tableau, but excited that I was able to create as much as this. Most of the elements included here are as previously discussed. The main change from my wireframe is the rotation of the "table" of visualizations.

To choose my color scale, I used coolors to both select my colors and check whether they would be safe for red-green colorblindness. The hex codes were as follows: Purple[#77146c #b738a8 #d381ca #e8bebe #d3a481 #b76f38 #773f14]Orange/Brown. I received some second-round feedback about the color scheme being weird and that I should just use red and blue, but I stubbornly decided not to change it due to the considerations previously mentioned. I felt that it would be confusing for the primarily American-UK readers of the paper if I were to represent the two sides of the political spectrum with red and blue, as the colors are switched between these countries.
##### Elections Included in this Paper
![redesigned viz](/dash2.png)

[Top](/TSWDPortfolio/critique2.md)
[Home](/TSWDPortfolio)
