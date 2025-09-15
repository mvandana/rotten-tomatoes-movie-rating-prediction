🎬 Rotten Tomatoes Movie Rating Prediction

**Summary**

Can we predict whether a movie gets a Fresh or Rotten rating, without ever reading a single review? That’s what this project set out to test.

Using a dataset of over 50,000 movies and critic reviews, I built a classification model that predicts a movie’s Rotten Tomatoes status purely from structured data like critic scores, audience counts, runtime, and content rating. No review text, just raw metadata.

**My Approach**

	•	Feature Engineering
	•	Combined two datasets: movie metadata and critic review stats.
	•	Engineered new features from critic vote counts (fresh, rotten, top critic).
	•	Encoded categorical variables like content_rating and handled missing values gracefully.
	•	Modeling Strategy
	•	Evaluated multiple tree-based models: Decision Tree, Random Forest, and XGBoost.
	•	Tuned hyperparameters and applied class weighting to handle imbalance between Fresh and Rotten labels.
	•	Assessed performance using accuracy, precision, recall, and F1-score.
	•	Performance Optimization
	•	Created custom ratios (like fresh/total critic ratio) to boost predictive signal.
	•	Used feature importance to prune irrelevant columns and improve generalization.

**The Impact**

	•	Final model achieved 99.2% accuracy, with strong performance on both majority and minority classes.
	•	Demonstrated that structured features alone can reliably forecast a movie’s Rotten Tomatoes status.
	•	Built a reusable, interpretable model pipeline that could be deployed or extended to streaming platforms.


**Business Value**

This project shows that you don’t always need full-text reviews to make smart decisions.

	•	Studios and distributors can use models like this for early prediction, before review embargoes lift.
	•	Streaming platforms can use it to optimize recommendation algorithms based on projected reception.
	•	Marketing teams can prioritize campaigns for movies predicted to go Rotten, or double down on Fresh ones.

When early data is all you have, this kind of model can still give you a valuable head start.
