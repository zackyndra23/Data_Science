# Data_Science

![Banner logo](https://github.com/zackyndra23/Data_Science/blob/main/Banner1.jpg?raw=true)

# Analysis of Bangkok Airbnb Listings Data
*by Zaky Indra Satria Putra, student at* &nbsp;
<a href="https://purwadhika.com" target="_blank">
    <img src="https://github.com/zackyndra23/Data_Science/blob/main/Logo%20Purwadhika.png?raw=true" width="20%">
</a>

<br>

# Context

Nowadays, when looking for accommodation, [Airbnb](https://www.airbnb.com/) is certainly one of the services that comes to mind.

<center><img alt="Analisando Airbnb" width="20%" src="https://news.airbnb.com/wp-content/uploads/sites/4/2020/04/Airbnb_Lockup_Over_Gradient.png"></center>


It works as an online marketplace that allows people to easily rent their homes, or rooms, to guests looking for a short-term rental.

Born in San Francisco, in 2007, Airbnb now has over 4 million hosts who have welcomed more than 1 billion guest arrivals, in about 100 thousand cities around the world [1].

This innovative business model generates a large amount of data. This attracts the data scientists, seeking to understand the dynamics involved as well as possible insights that could impact communities and the key partner especially **Guests**.

Within this scope, we will analyze data from the platform's top trending global destination during the year 2022: **Bangkok, Thailand** [2].

<br>

<div style="text-align:center;">
    <a href="https://www.jstage.jst.go.jp/article/urpr/10/0/10_243/_article" target="_blank">
        <center><img src="https://github.com/zackyndra23/Data_Science/blob/main/Bangkok1.jpg?raw=true" width="60%">
        <figcaption>Created by Querida Khotcharee on her article (click to read) </figcaption> </center>
    </a>
</div>

<br>

Bangkok is Thailand's capital and most populous city, a country located in Southeast Asia. Its popularity for tourism is due to the diversity of attractions that the city offers. There are any opportunities for us as a **Data Scientist** at AirBnB to attract the guest through the biggest value to **save money on rent**. In addition, the convenience of being able to choose a place according to all your preferences, only with the help of a device and **without having to negotiate with anyone**. Furthermore, the traveler can also **check the owner’s profile** and, in some cases, **exchange experiences with them during the stay**.

<br>

<div style="text-align:center;">
    <a href="https://travelwithjules.com/hostels-hotels/canal-house-bangkok-canal-next-door-airbnb" target="_blank">
        <center><img src="https://github.com/zackyndra23/Data_Science/blob/main/Bangkok2.jpeg?raw=true" width="60%">
        <figcaption>Photo by Jules on her travel blog (click to explore) </figcaption> </center>
    </a>
</div>

<be>
# Problem Determination

The data used in this analysis was obtained from the website [Inside Airbnb](http://insideairbnb.com/get-the-data.html), “a mission driven project that provides data and advocacy about Airbnb's impact on residential communities” [3].

The data has been simplified so that this [project](https://drive.google.com/drive/folders/1A_KBMRFTS5Mthpp46nulso679ML4ZwTF) is more specific in providing very useful and mind blowing insights.

In this project, company wants to know:
1. **Which neighborhoods** have the largest number of reviews while they're still having lack of completed stays?
2. What **parameters and patterns** have the potential to find 'hidden gems'?
3. **Which lodgings** still haven't received frequent reviews but there are a lot of completed stays and located in potential neighbourhoods?

Through this informations, it will helps company for:
- Giving some infos about potential neighborhoods that are not yet crowded so that guests/travellers are **more comfortable in enjoying their private holidays**
- Recommend listings from comfortable alternatives according to desired criteria such as price criteria, room type, number of nights stayed and superhost information **to increase guest satisfaction in choosing and planning a holiday**.
- Providing guests needs to find ***Hidden Gems*** or places that have a lots of reviews but are still not often visited by many people.

*“Potential Neighborhoods” refers to neighborhoods that guaranted to provide guests with an authentic local experience. This may include easy access to popular attractions, the presence of great local restaurants and shops, and a friendly and safe atmosphere. This kind of environment can increase the attractiveness of a property on the Airbnb platform because it offers guests the opportunity to experience daily life in the area.*

*A “hidden gem” refers to a listing that may not be well-known or widely exposed, but it has great value and offers guests a unique experience. Such listings are often not widely known to tourists, but provide a special experience, perhaps due to a unique location, attractive design, or exceptional service.*

A relevance table is order to describe the problem statement that the company wants to solve and its approach to achieving its goals. Relevance table of AirBnB Listings Bangkok:

| No. |                                    Problem statement (Company Curiosity)                                   |                                                                                                                                        Approching Methods                                                                                                                                        |
|:---:|:----------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| 1.  | Find potential neighborhoods for maximizing Airbnb's guest visit tendencies and recommendation strategies. | * Analyze the combination of factors such as pricing policy, reviews, number of valid listings, etc. <br> * Analyze the relationship between the number of valid listings and the number of reviews to understand trends and correlations.                                                       |
| 2.  |               'Hidden gems' identification in Bangkok's Airbnb listings at affordable prices.              | * Looking for price distribution patterns based on room_type in general. <br> * Finding out price categories in potential neighbourhoods. <br> * Analyzing the proporion of minimum nights stayed and availability for the next one year then looks at the relationship based on their duration. |                                                                                        



As a data analyst in AirBnB, we will try to solve the problems through the following questions:

**What are the characteristics of guests visiting Bangkok for the first time who want to use AirBnB to get a unique and private experiences?**

Let’s check out which ideas we can infer from the data.

<br>

# Conclusion and Recommendation

From the analysis that has been carried out, we can make the following conclusions about the 'Hidden gem', they are:
* The 15,846 data we have are used to see trends, general data distribution, and calculate data aggregation as a comparison.
* Potential neighborhoods, for example Bang Rak (reviews=21, listings=827), Khlong Toei, Ratchathewi, Vadhana, and Huai Khwang (reviews=16, listings=1123) were obtained from parameter analysis of the number of reviews and number of listings in the 20 Neighborhoods listed got the lowest number of reviews.
* General price distribution from the cheapest, such as shared room (med=500 THB), private room (med=1212 THB), entire home/apt (med=1536), then hotel room (med=1700). There are quite a lot of shared room and private room types available and the price range is still relatively cheap.
* The largest number of listings is in the price category range 1000 - 1999 THB, then 2000-2999 THB, then 0-999 THB.
* In the case of searching for 'Hidden gem', first thing first, the fewer the number of reviews in the neighbourhood, the greater the chance of getting a 'Hidden gem' listing. Even though it looks like a random pattern, the lower the number of reviews in a neighbourhood, the number of listings decreases and then increases.
* Analysis of 5 potential neighborhoods shows that the number of superhosts (3628) contributes 56.45% of the total number of superhosts, then contributes 34.63% to the number of newcomers (1876).
* The number of available reviews for Neighborhoods Khlong Toei, Vadhana, and Ratchathewi has decreased or is less than the number of reviews in the next 1 year. This indicates that these three neighborhoods are experiencing a decline in visitors

The characteristics of 'Hidden gem' listings in potential neighbourhoods, are as follows:
1. There is a big chance that it will be a private room type
1. Has relatively few total reviews
1. Characterized by a recent review that is not long in duration
1. Located in a neighborhood with a relatively small number of listings
1. In general, the minimum overnight stay is >1-3 nights
1. Have a listing pattern that has availability within the next 1 year, namely 3 - 6 months or more.

<br>

**Recommendation**
1. The definition of 'Hidden gem' can be approached more broadly but more accurately, such as adding further analysis related to local wisdom, location of tourist attractions, transportation access, etc. around the listings.
1. It is hoped that further development of this analysis can provide recommendations in the form of listings that meet the 'Hidden gem' target so that it can increase the level of guest satisfaction
1. Apart from having the potential to attract several key stakeholders such as investors, professional photographers and health insurance, it is hoped that this analysis can also be useful and make the company a leading company in innovation in this business field.
