A model created semi-supervised learning to detect whether a reddit title is clickbait or not. 
The initial supervised model is created by training a CNN by using a labeled dataset of406000 rows. 
Then by using that model pseudo labeling was done to the unlabeled dataset. 
Thereafter, a completely new CNN model was trained from combining both datasets.
