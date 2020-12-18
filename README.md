# project-6-Title-Detector
Title Detector
Through NLP and text classification, this project aims to classify a headline as clickbait or non-clickbait.

Clickbait refers to an article headline whose purpose is to use sensationalist language to lure in a viewer to click through to a certain webpage. That webpage typically generates ad revenue on the user's clicks or monetizes the user's activity data. The clickbait article itself is not written with journalistic integrity, research or really any deeper or practical meaning - it is simply a vehicle to grab clicks and activity.

52,000 headlines from clickbait and non-clickbait sources from roughly around 2007 - 2020 .
30,000: 2007 - 2016 headlines from https://www.kaggle.com/amananandrai/clickbait-dataset
22,000: 2019 - 2020 headlines that I scraped/requested from Twitter, APIs, online publications.
23,000:2019-2020.   headlines scraped from twitter of political parties in United States.
Clickbait sources: Buzzfeed, Upworthy, ViralNova, BoredPanda, Thatscoop, Viralstories, PoliticalInsider, Examiner, TheOdyssey


Non-clickbait sources: NY Times, The Washington Post, The Guardian, Bloomberg, The Hindu, WikiNews, Reuters

Process
Gather Data
Clean and process data, including feature engineering
Explore data through EDA for initial insights and understanding
Model & Evaluate : Used logistic Regression and used the model to classify new political party data

And finally Using this Model to Answer Question about  use of titles by political parties in United States

These Are the results i found:

CLICKBAIT TITLES FOR DEMOCRATS & REPUBLICANS
Clickbait Response across Democrats / Republicans: I see better clickbait response in Democrats. Overall 2500+ responders to clickbait titles. The percentage of clickbait titles is also higher in Democrats
                             
Additional data preparation done:
I could see many user comments / titles with nothing but empty spaces. All those were removed.
Analysis of Titles across different parties:
To make the analysis interesting I have taken Congressional districts / states which were Red / Blue as per 2016 election results. Then I have mapped these areas and tried to create analysis across 4 combinations;
Clickbait titles in Republican (Red) areas for Democrats:

In Red areas democrats are responding to corona virus related topics
Interestingly trump is also a key word for them in Red Areas
Democrats are promoting Mail-In vote as that is also a key term in Red areas

Clickbait titles in Democrat (Blue) areas for Democrats:
Top terms: Black, Women, Coronavirus, Died, War, Kids, Just
Themes closely resonating with ‘Black Lives matter’ movement
Core democratic voters targeted by clickbait titles: African Americans, Women

Clickbait titles in Democrat (Blue) areas for Republicans:
Unique terms: Vaccine, Mike Garcia (Republican Senator), China, Tax
Republicans are trying to create discussions around role of china in spreading virus
Also focused on titles for upcoming vaccine to tackle virus spread

Clickbait titles in Republican (Red) areas for Republicans:
Trump & Ted Cruz (names of two top republicans) are top clickbait titles
Biden (possibly with negative connotation) a strong clickbait topic
Twitter the medium of choice for communication for Donald Trump is also a top title word
Amy Coney 'Barett' the new appointee to Supreme court is also a top clickbait topic
