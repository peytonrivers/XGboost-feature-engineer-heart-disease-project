# XGboost-feature-engineer-heart-disease-project
In this project, I accomplished and learned a great deal about building and improving machine learning models. I began by developing an XGBoost model for heart disease prediction, achieving an initial accuracy of 76.3%. From there, I researched techniques to improve performance, starting with feature engineering: I binned the age column into meaningful groups, which improved accuracy to 78.2%.

Next, I studied the inner workings of XGBoost, particularly the effect of max_depth. I learned that smaller maximum depths are often better for smaller datasets, as they reduce overfitting and avoid modeling random noise. By adjusting max_depth, accuracy improved further to 80.3%.

Finally, I introduced the min_child_weight parameter, setting it to 3, which provided the best balance between underfitting and overfitting. This tuning step raised the model’s final accuracy to 81.2%.

Importantly, the model was balanced in its predictions: the classification report showed that it correctly predicted patients without heart disease 80% of the time, and correctly identified patients with heart disease 82% of the time.

Overall, this project was a significant milestone in my journey to becoming a stronger data scientist. I not only improved model performance, but also gained hands-on experience with feature engineering, model tuning, and performance evaluation, all of which are essential tools for adapting machine learning models to achieve higher accuracy.
