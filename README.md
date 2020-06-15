# A-B_Testing
This project is part of Udacity's Data Science Nanodegree program as a portfolio exercise.
Data is provided by Udacity through Starbucks.

In the experiment simulated by the data, an advertising promotion was tested to see if it would bring more customers to
purchase a specific product priced at $10. Since it costs the company 0.15 to send out each promotion, it would be best to
limit that promotion only to those that are most receptive to the promotion.
In this notebook, we try to maximise a few buisness metrics that are related to increased purchase of the promotional drink.

In this notebook, we categorized the data as follows:
People who got the promotion (1); but did not buy (0)
People who got the promotion (1); and bought (1)
People who did not get the promotion (0), and did not buy (0)
People who did not get the promotion (0), but bought anyway (1)

We  trained two seperate models, one with datapoints that recieved the promotion (experiment group) and one with datapoints that
did not receive the promotion (control group). The lables were be if they purchased the new product or not.
We got two sets of probabilities, and the difference in them gave us the likelihood of a person, not given the promotion, 
who would more likely buy the product, if given the promotion.
