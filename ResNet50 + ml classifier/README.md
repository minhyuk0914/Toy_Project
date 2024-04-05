# Multi-Class Image Classification

* Quiz : 이미지를 10가지 항목으로 분류
* Data = keras.dataset.fahion_mnist
* ResNet50 = keras.applications.resnet.ResNet50
* Metrics : Accuracy_score

* ResNet50
![image](https://github.com/minhyuk0914/DL_study/assets/90814001/0e04c28b-df4b-42c6-b09b-76f4cefd4b08)


**HOW TO ML**
> 1. ResNet50.layers[-1] == avg_pool(dimension - 1) -> feature_extractor
> 2. (train & test)_features = feature_extractor.predict(train & test)
> 3. ML Classifier.fit(train_features, train)
> 4. ML Classifier.predict(test) or ML Classifier.score(test dataset)
