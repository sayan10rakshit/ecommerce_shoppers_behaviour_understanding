# E-commerce Shopper's Behaviour Understanding

 Understand the online shopper purchasing pattern through Machine learning

## Competition Description

- Visit the competition page ➡️ [competition page](https://www.kaggle.com/competitions/e-commerce-shoppers-behaviour-understanding/)

- Visit Leaderboard ➡️ [leaderboard](https://www.kaggle.com/competitions/e-commerce-shoppers-behaviour-understanding/leaderboard)

**Rank - 7;
Team Name - 21f1002696**

The competition is to predict whether a user has made a purchase or not. The dataset contains the following columns:

### Columns
The first six columns represent the different pages in the e-commerce website visited by a user from other sites.

- **HomePage**: Number of times visited this page
- **HomePage_Duration**: Total number of duration spent on this page.
- **LandingPage**: Number of times visited this page
- **LandingPage_Duration**: Total number of duration spent on this page.
- **ProductDesriptionPage**: Number of times visited this page
- **ProductDescriptionPage_Duration**: Total number of duration spent on this page.
- **GoogleMetric-Bounce Rate**: Whenever a user comes to any one web-page of the website and he/she does not go to any other page and exits from the website from the same page, then this activity done by the user is called Bounce. And the percentage of the total number of times the user visiting our website and bounce it, is called Bounce Rate
- **GoogleMetric-Exit Rate**: The bounce rate is calculated based on the user exiting a website after visiting one page. But some users exit from the second, third, fourth, or any other page of our website, then those visitors’ data help determine the exit rate. The percentage of the total number of times the user to our website who do not exit from the first page (Landing Page) but exit after exploring other website pages is called the Exit Rate.
- **GoogleMetric-Page Value**: Page Value is the average value for a page that a user visited before landing on the goal page or completing an Ecommerce transaction.
- **SeasonalPurchase**: It is a weight indicator to track the seasonal purchase. If a user makes a purchase during any seasonal time (Mother’s Day, Diwali, Valentine's Day), we will assign based on internal heuristic.
- **Month_ SeasonalPurchase**: Month of the special day considered for seasonal purchase.

The other attributes like, OS, Search Engine, Zone, Type of Traffic, Customer Type, Gender, Cookies Setting, Education, Marital Status and Weekend Purchase are self-explanatory variables

## Dependencies

- Scikit-learn
- Imbalanced-learn
- Pandas
- Numpy
- Matplotlib
- XGBoost

## Info
>
> [!NOTE]
> This competition was hosted by MLP Project team of IIT Madras BS Degree [^1].

[^1]: [study.iitm.ac.in/ds](https://study.iitm.ac.in/ds/course_pages/BSCS2008P.html)
