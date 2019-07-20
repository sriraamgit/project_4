# project_4
The libraries used in this project are the numpy, pandas, matplotlib, seaborn 

Motivation:
    My motivation to choose the dataset is,Happiness Reporte are given recently from seven years based on some Countries. I want the people to be happy at the root level because that increases the Happiness score of a Country, by being Positive first, do good things, then be Happy.I have explained a little in my blog about this, here I have taken this dataset to do some statistics.    
    The present state of affairs of the people in the society, where they think that they can do anything what they like, following short-cuts like, some people want to attain wealth overnight without working hard, some people want a Master’s degree overnight without studying, which is wrong.
Personally I have been motivated a lot from the following, which give me the required discipline ,
My Guru’s words,
The music of Divine Mother of Pondicherry,
Napoleon Hill’s book ‘The essence of Law of Success”,
Rudyard Kipling’s poem “IF”,
    

Files in the Repository:
       world-happiness-report-2019.csv   This is the dataset file in .csv format
       The World Happiness Report is a land mark survey of the state of global happiness that ranks 156 countries by how happy their citizens perceive themselves to be.
       country_happiness.ipynb    This is the code file
       It is a jupyter notebook file consisting of plots and code         
       
Results of the analysis :
       Do you think the people of different Countries are happy equally?
What type of attitude do people develop because of Positive emotions ? 
What type of attitude do people develop because of negative emotions?
Is the data collected about a Country reliable?

The answer for the first question is that people belonging to a Country are happy to a certain extent based on the Policies their government undertakes. As we can see from the figure the Arabic Countries which are developed like Syria, Iraq, Lebanon, Yemen etc. are having people with a high emotion of PositiveAffect.
The people of Countries like Costa Rica, Paraguay, Somalia etc. which are underdeveloped Countries have people with less value for PositiveAffect.
Here I have found that for Qatar, as there is no value for PositiveAffect we have substituted it with mean value in the code, but all the Arabic Countries are having a high value of PositiveAffect. So I want to highlight the point that it is not always correct to substitute mean for missing values.
 We can say that the people of the developed Countries are more happy than the people of underdeveloped Countries.
The figure shows in green for the Countries whose contribution of emotion of Positive Affect is satisfactory and in red for the Countries which have to design their Government policies for the development of the Country in a way to improve the emotion of Positive Affect of their people finally imparting happiness to them.

The answer to the second question is that, by viewing the intensity of data points  in the scatter plot, we can say that, the emotion of PositiveAffect also inculcates a quality of Generosity to a large extent as a Positive mind always thinks of being good and they both contribute much for the Happiness Score of the Country.

The answer to the third question is that, the emotion of NegativeAffect and the extent of perception of Corruption are to an extent related to each other as the Negative mind to a certain extent is  a cause for Corruption like attitudes which can be seen from the intensity of data points in the plot. These both are bad qualities and should be less for the best Happiness Score of the Country.

The answer to the fourth question is that, Statisticians say that a regression model fits the data well if the differences between the observations and the predicted values are small and unbiased. Unbiased in this context means that the fitted values are not systematically too high or too low any where in the observation space. As the r2_score is 0.664520, we can infer that the data collected to a certain extent forms a good collection without much bias.
