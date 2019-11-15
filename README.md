# Pocket

## Table of Contents
  * [Collaborators](#team-members)
  * [Introduction](#intro)
  * [Project Demo](#proj-demo)
  * [Limitations](#lim)
  * [Future Prospects](#var)
  * [Appendix](#app)
  
## <a name ="team-members"></a> Collaborators
* [Muskaan Goyal]
* [Ewen Dai]
* [Gayatri Babel]
* [Huiyi Zhang]

## <a name ="intro"></a> Introduction
* In this project, we attempt to create a financial application which utilises IBM Z to update and analyze users' budget allocations in real-time based on spending patterns and provides relevant daily insights into federal and campus resources. We implement this idea using user-user collaborative filtering and recommending algorihtm.  

* Note: Pocket was created during IBM X DSS Datathon for Social Good in November 2019 where the project won the **first prize** in the datathon.

* Look at our slides for the datathon here: https://tinyurl.com/project-pocket.

## <a name ="proj-demo"></a> Project Demo
**DESIGN**
<p align = "center"><img src = "Screen Shot 2019-11-13 at 5.27.42 PM.png"></p>

**USER JOURNEY**

* **Step 1**: Set your total budget & take the introductory survey
* **Step 2**: Link credit card(s), submit receipt pictures, or input entries manually.
* **Step 3**: Informational graphs will come to life and help you keep track of how you are spending and how much.
* **Step 4**: Rate recommendations made for you based on usefulness.
<p align = "center"><img src = "Screen Shot 2019-11-13 at 5.27.19 PM.png"></p>

## <a name ="lim"></a> Limitations
**1. Past Financial Constraints**: The algorithms depends on past financial budget and spending. As we wouldn't have past budget for new users, the quality and quantity of tips can vary depending on the user.

**2. Quality and Quantity of Tips**: To release new recommendations regularly for the users we need a good quantity of tips while mainting their quality.

## <a name ="var"></a> Future Prospects
* Functionality to add customisable trackers. eg. add tracker for subscriptions. 
* Add location based recommendation functionality to the algorithm to provide with better recommendations/tips.

## <a name ="app"></a> Appendix
* User Based Collaborative Filtering using N-Nearest Neighbours: https://medium.com/sfu-big-data/recommendation-systems-user-based-collaborative-filtering-using-n-nearest-neighbors-bf7361dc24e0
* Recommendation System: https://github.com/ashaypathak/Recommendation-system/blob/master/Movie_Recommendation.ipynb
* Collaborative Filtering: https://en.wikipedia.org/wiki/Collaborative_filtering#Memory-based
* Locality-sensitive Hashing: https://en.wikipedia.org/wiki/Locality-sensitive_hashing
* Locality-sensitive Hashing: https://pypi.org/project/LocalitySensitiveHashing/
* Python Recommendation Engine: https://www.analyticsvidhya.com/blog/2018/06/comprehensive-guide-recommendation-engine-python/

[Muskaan Goyal]: https://github.com/muskaangoyal
[Ewen Dai]: https://github.com/ewendai
[Gayatri Babel]: https://github.com/gayatribabel
[Huiyi Zhang]: https://github.com/huiyiz
