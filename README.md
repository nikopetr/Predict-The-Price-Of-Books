# Predict-The-Price-Of-Books

<p align="center">
  <img src="https://github.com/nikopetr/Predict-The-Price-Of-Books/blob/main/images/book-g15de16620_1920.jpg" width="800" height="400"/>
</p>

For this task, a big dataset which consists of book of different genres and authors was utilized. The provided dataset included various book features, such as Author, Edition, Reviews, etc. Those features have been used as regressors in order to predict the price of books, using various proposed methods and models.

**Author**: Nikolas Petrou, MSc in Data Science

### Technical-Report and Code Availability
- A complete file-folder guide is located in the **folder-file guide** folder
- The technical report and analysis of the work is available and located in **report.pdf** file
- The implementation and code of the project is located in the **code files** folder

## Dataset Overview
Regarding the data of this work, there is an online competition for this task, which has been up since 27/09/2019. Currently, the competition has 3579 participants in total. The data was downloaded directly from [MachineHack](https://machinehack.com/hackathon/predict_the_price_of_books/overview). There were two files forthe train and test sets. The training and test sets included 6237 and 1560 records respectively. In addition, the values of the target variable (Price) were not included in the test set, as the evaluation of the test set is employed through the website of MachineHack.

## Methodology

Some of the key methods which were used throughout the work are:
- Visualization
- TF-IDF and LDA Topic Extraction
- Text-tranlsation using Google Trasnlate Ajax API
- Cyclical feature encoding for time-based feature extraction
- Price Prediction using different conventional and advanced algorithms (e.g. GBM, RF, SVM, CatBoost, LightGBM)

An abstract methodology scheme of the work is illustrated in the following Figure.

<p align="center">
  <img src="https://github.com/nikopetr/Predict-The-Price-Of-Books/blob/main/images/predict_books_schema.png" width="750" height="400"/>
</p>

Summarizing, firstly the exploratory data understanding process was commenced. Each feature was assessed in order to obtain a better understanding of what it represents and how it could affect book pricing. Next, each future was brought into a format that was appropriate for model development. Following, through visualization, it was examined how the different features were correlated to the dependent-target variable. Furthermore, the processed data were used to implement the employed models. The prediction-modelling phase was conducted with two different approaches. Finally, the whole methodology procedure followed a cyclical behaviour, until the final prediction model was implemented.
