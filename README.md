# Energy_Efficeincy in Residential Buildings.
## project description

project overview

Dataset

Workflow


Organisation

links



### project overview

The aim of this project is to create a prediction model for Energy loads in buildings using machine learning algorithms and focused on  how it physical charateristics influences it energy consumption. Cooling loads and heating loads where used a benchmark to measure energy comsumption in this project.

###  Dataset

 The dataset was obtianed from kaggle and it contained analysis performed on 12 different building shapes simulated in Ecotect. The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. The dataset comprises 768 samples and 8 features, aiming to predict two real valued responses.

Attribute Information:

The dataset contains eight attributes (or features, denoted by X1…X8) and two responses (or outcomes, denoted by y1 and y2). The aim is to use the eight features to predict each of the two responses.

Specifically:

X1 Relative Compactness

X2 Surface Area

X3 Wall Area

X4 Roof Area

X5 Overall Height

X6 Orientation

X7 Glazing Area

X8 Glazing Area Distribution

y1 Heating Load

y2 Cooling Load

[link to dataset](https://www.kaggle.com/elikplim/eergy-efficiency-dataset)

### Workflow

1) I started by bordening my understanding about the dataset by reviewing various scientific literature about energy efficiency in buildings.

2) Statistical analysis and pre-processing was performed via Jupyter.

3) The dataset was thoroghly  examined for outliers and subsequently spot checked with various machine learning algorithms using k fold cross validation to get the best performing model.

4) The dataset was later splited into train and test sets to validate the spot checked results and also check for feature importance.

5) Grid search and Recursive Feature Elimination  was using in improving the results of the best performing. 


### Organisation
1) README.md file explaining the project
2) Data folder with all csv files, described under dataset
3) Data_analysis folder with the models and statistical analysis, described under data analysis.
4) Tableau, with the link to the tableau

### links

(Accurate quantitative estimation of energy performance of residential buildings using statistical machine learning tools)[https://www.sciencedirect.com/science/article/abs/pii/S037877881200151X]

Analysis of the best building orientation[https://www.researchgate.net/figure/Analysis-of-the-best-building-orientation_fig6_259994568]





