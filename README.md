# Machine Learning Project Steps

Most machine learning projects follow a similar outline. This outline will be helpful tackle any machine learning problem.

**Project Steps**

1. Form a hypothesis.
2. Find and explore the data.
3. (If necessary) Reshape the data to predict your target.
4. Clean the data for ML.
5. Pick an error metric.
6. Split your data.
7. Train a model.

File overview:

* `machine_learning.ipynb` - the main project code
* `data_prep.ipynb` - the code to generate the team-level dataset from an athlete-level dataset

# Local Setup

## Installation

To follow this project, please install the following locally:

* Python 3.8+
* Python packages
    * pandas
    * numpy
    * scikit-learn
    * seaborn


## Data

We'll be using data from the Olympics, which was originally on [Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results).

You can download the files we'll use in this project here:

* [teams.csv](https://drive.google.com/uc?export=download&id=1L3YAlts8tijccIndVPB-mOsRpEpVawk7) - the team-level data that we use in this project.
* [athlete_events.csv](https://drive.google.com/uc?export=download&id=1Ah4wOyNFMGREq8Yw_Jbv7u2CeI_6tpn5) - this is the original athlete-level data
