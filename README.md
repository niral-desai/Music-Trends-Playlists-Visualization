# Music-Trends-Playlists-Visualization
A data visualization project using Python and Tableau to analyze music listening trends and user playlists. Generate graphs to gain insights and create visually appealing representations of the data. Ideal for artists and music enthusiasts alike.
IE 6600 - Computation and Visualization
for Analytics
Final Report
Group 11
Music Data Visualization System
Aishwarya Sardae
Niral Desai
Prakhar Gupta
Rishabh Khosla
INTRODUCTION
Listening to music is a popular pastime, the experience can be further enhanced through visual representations that allow for a more immersive and interactive experience. The Spotify Million Playlist Dataset Challenge consists of a dataset and evaluation to enable research in music recommendations.
We populated our dataset with a wide library of songs ranging across various genres to analyze and generate insights about the current music listening trends The goal of such a system would be to provide insights and understanding about the music available on the platform, allowing analysts to make more informed decisions about what to listen to, how to market music, and more.
The objective of this project is to perform visualization on Music dataset that includes different factors like songs, artist names, lyrics, and more.
To perform a thorough analysis and generate meaningful visualizations, we will combine various Kaggle datasets to produce the most suitable dataset containing all the necessary fields.
The main goals of our case study are:
 To generate information for artists about the current music listening trends. This helps artists gain knowledge about what music is trendy in the present day and therefore giving them a chance to dabble in it.
 To help users have accessibility to their favorite music with playlists. A premium account user has ability to create playlists where they can add their favorite music.
The dataset was collected from Kaggle and comprises of a diverse selection of entries.
https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset
https://www.kaggle.com/code/aeryan/spotify-music-analysis/notebook
https://www.kaggle.com/datasets/maltegrosse/8-m-spotify-tracks-genre-audio-features
DESIGN FLOW
The design flow of a Spotify music Visualization system starts with the collection of relevant data, such as user preferences, playlists, and listening history. This data is then preprocessed, which involves cleaning, filtering, and transforming it into a suitable format for analysis. Once the data is ready, it is connected to the data source and analyzed to extract meaningful insights. These insights are then used to create an interactive dashboard that presents personalized music
recommendations to users. Finally, the inferences drawn from the system are presented to users for their feedback and further improvement of the music system.
DATA PREPROCESSING
Data cleaning is an essential part of preparing data to ensure its reliability and consistency. In the report below, you will find an explanation of why data cleaning is necessary, as well as the code used to perform the cleaning process.
When conducting data analysis, missing values can greatly influence the results. Thus, it is crucial to handle them properly. This dataset's missing values are indicated by NaN (Not a Number) values.
Data wrangling and transformation are essential steps in the data analysis process, as they ensure that the data is properly cleaned, organized, and prepared for analysis. By conducting these steps effectively, the data can be analyzed more efficiently and accurately, which can lead to more insightful conclusions and better decision-making.
Data processing for a Spotify music Visualization system involves several steps, such as cleaning and filtering the data to remove inconsistencies and irrelevant information. The data is then transformed into a suitable format for analysis, such as a matrix of user preferences and music features. This processed data is then used to build and train a recommendation model that can provide personalized music recommendations to users based on their listening history and preferences.
1. The NULL values have been replaced my mean of the column
2. Unwanted columns have been dropped
3. Datatype of date column has been changed to DateTime
Correlation and Heatmap of the Dataset
VISUALIZATIONS
Line Plot to show Number of songs released for different genres each year:
From the above line graph, we can infer the following:
• Pop music has increased the most over the span of 20 years.
• Reggae has seen the most fluctuation in the last 2 decades.
• Classical music has been the only consistent genre among the users.
Comparing different genre of songs on the basis various parameters and plotting them using a bar graph:
Based on the four bar graphs that show the variations in acousticness, danceability, energy, and instrumentalness across different music genres, here are some insights:
1. Classical music has the highest acousticness values compared to other genres. Jazz and blues also have relatively high acousticness values, while hip-hop has the lowest acousticness values. This may be because hip-hop typically relies on electronic beats and samples, which are less acoustic in nature.
2. Electronic music has the highest danceability values compared to other genres, which is not surprising given its focus on electronic beats and dance-oriented rhythms. Hip-hop and pop also have relatively high danceability values, while classical music has the lowest danceability values. This may be because classical music is not typically associated with dance-oriented rhythms and is instead more focused on melody and harmony.
3. Electronic music has the highest energy values compared to other genres, which is again not surprising given its focus on electronic beats and high-tempo rhythms. This may be because classical music is not typically associated with high-energy, high-tempo rhythms and is instead more focused on emotion and expression.
4. Classical and electronic music have the highest instrumentalness values compared to other genres, which is not surprising given their focus on instrumental compositions and electronic production techniques. This may be because hip-hop and pop typically rely on vocal performances and electronic instrumentation, rather than instrumental compositions.
Finding the trends in the popularity of songs of various genre over the years using line plot:
Pie chart to show the percentage of users across various genres of music
• Overall, citizens of United States have the maximum number of users by a significant amount.
• The collection of electronic music is the highest
1. Most users on Spotify are premium users, with 71% of users paying for the service. This indicates that the company has been successful in convincing a significant portion of its user base to upgrade to the paid version of the app.
2. Out of the premium users, most users are on the yearly plan, with 94% of premium users opting for the annual subscription. This suggests that users find it more convenient and cost-effective to commit to a longer-term subscription.
3. The remaining 6% of premium users are on the monthly plan. This could be because they prefer more flexibility and do not want to commit to a long-term subscription. It could also be an indicator that they are not using the service frequently enough to justify the cost of the yearly subscription.
Overall, the insights indicate that Spotify has been successful in converting a large portion of its user base to paid subscribers, and most of these users prefer the yearly subscription plan. However, the relatively small percentage of users on the monthly plan highlights the importance of flexibility and affordability for some users, and it suggests that Spotify could benefit from offering more subscription options to cater to different user needs.
TABLEAU ANALYSIS
Tableau Analysis on Spotify Music Visualization System involves using the Tableau software to create insightful visualizations from the Spotify Million Playlist Dataset. The objective is to generate meaningful visualizations that will help analysts gain insights and understanding about the music available on the platform. This, in turn, allows them to make more informed decisions about what to listen to, how to market music, and more. By using the dataset, we can gain knowledge about the current music listening trends, which helps artists understand what music is trending in the present day and gives them a chance to explore and create similar music. Additionally, the visualizations will help Spotify users gain accessibility to their favorite music by creating personalized playlists. With Tableau, we can create stunning visualizations and dashboards that will allow us to analyze the data in an interactive and engaging way.
The visualization graph shows the number of Spotify users on a choropleth map, with the highest number of users located in the United States, followed by Russia, and the least number of users in countries like India and parts of South Africa. Here are some key points to elaborate on this graph:
1. The map highlights the dominance of the United States in terms of Spotify users. The country has the highest number of users compared to any other country in the world, which indicates the popularity of the music streaming service among Americans.
2. Russia, with the second-highest number of Spotify users, demonstrates the platform's growing popularity among Eastern European countries. This is a significant achievement for Spotify, as the region is known for its preference for local music platforms.
3. On the other hand, the map reveals the low number of Spotify users in countries like India and parts of South Africa. This could be attributed to several factors, including low internet
penetration rates, cultural preferences for other music platforms, and lack of local content on Spotify.
4. The map also shows that Spotify has managed to capture a significant share of the market in several European countries, such as the UK, France, and Germany, where the number of users is considerably high.
5. Finally, the visualization graph highlights the potential for growth in untapped markets such as Asia and Africa, where Spotify has not yet penetrated fully. With increasing internet penetration rates and a growing demand for online music streaming services, Spotify can leverage this opportunity to expand its user base and increase its revenue streams.
Line graph indicating different Song Genres for the count of Release throughout different Decades
1. The graph shows the number of songs released over the years across different genres.
2. We can see that pop music has seen a significant increase in the releases after the year 2016.
3. Number of classical releases has faded out throughout the years.
Bubble chart showing the Spotify users from different Countries
• A packed bubble chart is a type of data visualization that displays data points in the form of bubbles, where the size of the bubble represents the magnitude of the data point. In a packed bubble chart, the bubbles are arranged in a compact way, with smaller bubbles nested within larger bubbles to show hierarchical relationships.
• Based on the packed bubble chart that displays the countries with the maximum Spotify listeners, here are some insights:
1. The United States has the highest number of Spotify listeners, which is not surprising given its large population and the popularity of music streaming services in the country. This suggests that Spotify has been successful in attracting a significant number of users in the US market, which could be due to its user-friendly interface, personalized recommendations, and wide range of music offerings.
2. China has the second-highest number of Spotify listeners, which is interesting given that Spotify is not available in China due to government restrictions. This could indicate that many Chinese users are accessing Spotify through VPNs or other workarounds, or that the data is reflecting the number of Chinese users who are listening to Spotify while traveling abroad.
3. The United Kingdom and Indonesia also have a significant number of Spotify listeners, which suggests that Spotify has a global reach and has been successful in attracting users from different parts of the world. This could be due to its localized content offerings, partnerships with local artists, and efforts to understand and cater to the diverse music tastes of different regions.
4. The packed bubble chart shows that there are other countries with smaller but still significant numbers of Spotify listeners, which highlights the importance of understanding and catering to the preferences of users in different regions. This could involve offering more localized content, partnering with local artists and labels, and using data analytics to identify emerging music trends and genres in different regions.
KEY TAKEAWAYS
1.The number of Spotify users varies significantly by country, with the United States having the highest number of users, followed by Russia, and lower numbers in countries such as India and parts of South Africa.
2. The characteristics of music genres vary significantly based on different features, such as acousticness, danceability, energy, and instrumentalness. For example, classical music tends to have the highest acousticness, while electronic music tends to have the highest danceability and energy.
3.Most Spotify users are premium subscribers, with most of these users choosing the yearly subscription plan. However, a small percentage of users opt for the monthly plan, indicating the importance of flexibility and affordability for some users.
5.The packed bubble chart highlights the global reach of Spotify, with significant numbers of users in different regions, suggesting the importance of offering localized content and understanding the diverse music tastes of different regions.
Overall, these insights suggest that Spotify's success is due in part to its ability to cater to the diverse music preferences of its global user base, while also offering flexible and affordable subscription options.
STRATEGY GOING FORWARD
1. Increase efforts to expand Spotify's user base in regions with lower numbers of users, such as India and parts of South Africa, through targeted marketing and localized content offerings.
2. Further explore the characteristics of different music genres and use this information to inform music recommendations, personalized playlists, and other features that enhance the user experience.
3. Continue to offer flexible and affordable subscription plans to attract and retain users, while also exploring new revenue streams, such as advertising and sponsorships.
4. Further leverage data analytics to gain insights into emerging music trends and genres in different regions, which can inform content offerings and partnerships with local artists and labels.
5. Invest in research and development to explore new technologies and features that can enhance the user experience, such as machine learning and AI-based recommendation systems, voice-enabled music search and playback, and virtual concerts and events.
6.
Overall, these strategies can help to further cement Spotify's position as a leading music streaming service, while also expanding its reach and appeal to new users and markets.
SUMMARY AND RECOMMENDATIONS
The objective of this system is to offer valuable insights and comprehension about the music present on the platform. This will help analysts in making well-informed decisions regarding music selection, marketing strategies, and other related areas. To conduct a comprehensive analysis and create insightful visual representations, we will merge different datasets from Kaggle to create the most appropriate dataset that includes all the required information.
Through the visualisations we can state that the popularity for each genre is different for different parameters of a song. While a song might have high danceability, it might have low acousticness. This helps artists in understanding what kind of parameter a song needs to have to achieve the goal behind its creation. Following that, we also have information about the popularity of genres through time. This helps artists stay up-to-date with the listening habits of their audience and can therefore release more music of the liking of the audience. Our objectives to allow artists to be parallel users of the service and providing users functionality to create their own playlists have also been accomplished.
The various advantages of this case study are:
 By providing an open space for music, we predict that more people will be willing to experiment with music.
 Creating playlists comes at an advantage of its own as it allows users easy accessibility to the music of their liking.
 Artists can identify the enjoyability of their music because of the analysis we performed on the various characteristics of the song.
 It helps artist understand the popularity of individual genres in the current scenario.
