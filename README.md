# ECE491-Data-Science-for-Social-Good
### Nithilam Subbaian, Jessica Martinez, Raymond Ming Lee

City Harvest is New York City’s largest food rescue organization, rescuing up to 61 million pounds of food in 2019 and delivering it to food pantries, soup kitchens, and other community partners. Currently, helping to feed more than 1.2 million New Yorkers struggling to find food, City Harvest has the goal to end hunger in communities by distributing food, educating the community, and finding solutions to end food insecurity.

#### Our goal: To provide an overview of the food landscape in neighborhoods, aiming to identify group needs and explore solutions on a community level.

# Project 1: 
We created a website that charted out the meals served in the various city community districts over the years. We implemented this visual so that the user can click through the various years and see how the distribution and concentration of meals served changed over the years in New York City. To accomplish this, we used glitch.com, which allowed us to use html and css along with other tools such as photoshop and glitch to display this information. This visual will help us assess the effect of different events on how they affected food supply needs by analyzing factors such as how quickly food supply changed or moved to an area affected by a city event, how quickly that city grew or recovered after a disaster, etc. Initially we had hoped to correlate the changes in meals served with events that happened in NYC, but quickly learned that this was not possible with the limited data that we had, so we then shifted our focus for this project to display the information that we had from the the organization FeedNYC and City Harvest to visualize the data and show the breakdown of each year and demographics so the user can interpret the data. We changed the layout and content of the website over the comments we received such as changing the color scheme to a more lively version with colors that City Harvest uses, as well as including a GIF to summarize the information. We displayed this project in the form of a tablet on the day of the presentations.
Here is a link to our website: https://nycity-meals.glitch.me/

![GitHub Logo](/images/glitchScreen.png)

# Project 2:
We implemented machine learning to analyze how different aspects of a community impact food insecurity. We went through different features to find their relation with labels of meal gap, supply gap, and food insecurity population. At the end, we decided to use the features of Percent of population with a H.S. Degree, Percent of Population with a college degree, Unemployment Rate, Percent of Population under the Poverty Line, and Population not U.S citizen. The model we chose is Lasso Regression, which is commonly known for getting input-output like relationship for a Machine Learning regression. Moreover, Lasso regression allow us to tune the freedom of the model in order to find which are the most correlated features. As freedom decrease, Lasso model would assign zero weight to less correlated input features. This behavior leads us to the final 5 features that we use for the model. During the training process, 10 out of 195 NTA district were selected randomly as validation set. And 10% of the remaining data were chose randomly as the test data set. The model was trained until the loss (mse) on validation set is about 0.01(normalized). 

For this project we used this model to create an interface that allows the guest to “Design their own City”. Essentially, the interface opens up with an explanation of City Harvest and their goals, then breaks down the data that they provided us with and how we combined that with Open Source data to learn how the features we selected effect meal gap, supply gap and food insecurity population. Then the interface allows the user to view the data for East Village and compare it to a location in NYC of their choice. Finally, once the user understands the data and the model, the user is allowed to alter the values for the features to “Design their own City” to see how these features of Percent of population with a H.S. Degree, Percent of Population with a college degree, Unemployment Rate, Percent of Population under the Poverty Line, and Population not U.S citizen affected the City’s Meal Gap, Supply Gap, and Food Insecurity Population.

Here is screenshots of our model at the presentation and the code is attached for “Design your own City”:

![GitHub Logo](/images/chALL.png)

# Project 3:
Ee represented the meals served at the food banks in a humanistic approach through a physical art piece, or soft sculpture. To create this soft sculpture, we found a basket and paper mached it to make a large bowl, and painted it with a lively color, similar to the yellow theme we used in a our previous projects for continuity. We then found facts about food insecurity and screen printed them on canvas, and made rice shapes stuffed with actual rice. We then filled the bowl without canvas rice and actual rice. The goal of this project was to display the jarring facts about food insecurity in a tangible manner that allows the guests to interact with the design, and feel for the different facts in the rice. The open bowl asks for the guests to explore and learn more about the effects of food insecurity. We also filled the canvas rice with actual rice so that guests can take one home with them, in an effort to not waste rice, which follows with the goal of City Harvest to redistribute food.


![Rice Bowl](/images/riceBowlCloseUp.jpg)

We worked initially with Gabrielle Williams, who is the assistant manager for Agency Relations at City Harvest who we have met in person, to obtain more data on City Harvest. We used data from City Harvest, FeedNYC, and Open Source data about NYC to complete our project. We had a lot of fun creating our projects and hope that the guests had fun interacting with them at the final presentation. Thank you to Prof. Keene and Prof. Woods for helping with every iteration of our project.


