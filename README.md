# bank
bank-ml-model

The dataset was gotten from 
http://archive.ics.uci.edu/ml/machine-learning-databases/00222/.


Customer Service from a bank in Portugal called certain people to know if
they will subscribe to a term deposit, the folks signified with YES or NO

Problem Statement
	Build a model to predict if a client will subscribe to  a
	term deposit(fixed-term investment into an account).

- bank.csv contains the csv file.

- bank-names.txt contains information about the the file(it explains the 
various attributes) and give necessary infrmation about the dataset

- BANK.ipynb is a jupyter notebook where the analysis, visualization 
on the dataset were carried out

FURTHER ANALYSIS
	It was noticed that there was an imbalance in the target(
	about 88% of the class people contacted said 'NO' while the others
	said otherwise.

	The dataset was resampled using the sckit-learn resample function to get
	the same percentage of YES and NO by adding to the number of people that
	said YES.

	The Visualization, Inferences and Models are in the BANK.ipynb

	A Decision Tree Classifier proved to be the most effective with an
	accuracy of over 85%.

