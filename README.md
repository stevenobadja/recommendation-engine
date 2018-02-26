[![movies](80s-movies.jpg)](80s-movies.jpg)

# What should I watch?

**Overview:**<br/>
Using movies & ratings datasets we will create two recommendation engine to predict what movies we should watch. Both engines will use **collaborative filtering** as the preferred method:
1. Item to item
2. Hybrid: User to user, followed by item to item

In a general sense, the engine will group similar users and similar items.

**Method:**<br/>
Typically, the workflow of a collaborative filtering system is:

1. A user expresses his or her preferences by rating items (e.g. books, movies or CDs) of the system. These ratings can be viewed as an approximate representation of the user's interest in the corresponding domain.[![melbourne]
2. The system matches this user's ratings against other users' and finds the people with most "similar" tastes.
3. With similar users, the system recommends items that the similar users have rated highly but not yet being rated by this user (presumably the absence of rating is often considered as the unfamiliarity of an item)

A key problem of collaborative filtering is how to combine and weight the preferences of user neighbors. Sometimes, users can immediately rate the recommended items. As a result, the system gains an increasingly accurate representation of user preferences over time. ~ Wikipedia (https://en.wikipedia.org/wiki/Collaborative_filtering)<br/><br/>
[![movies](met_21_4_493_fig1a.gif)](met_21_4_493_fig1a.gif)

**Dataset:**<br/>
The dataset can be found at: (https://www.kaggle.com/rounakbanik/the-movies-dataset)
<br/><br/>