# 1. Install Packages

- Create a virtual environment and activate it
- Install required packages with:

    ```{python}
    pip install -r requirements.txt
    ```

## Distribution of Training Dataset

– Age distribution of the train and validation cohorts

<p float="left">
  <img src="figures/train_distribution.png" style="width:45%; height:auto;"/>
</p>

- XGBoost results on BHRC

## Forbow Distribution & brain age prediction
<p float="left">
  <img src="figures/sobp_testing_distribution.png" style="width:45%; height:auto;"/>
  <img src="figures/bhrcsobp_brainage_age.png" style="width:45%; height:auto;" /> 
</p>


## Familial Risk, ADHD, Anxiety
- Plots showing that there are no differences in brain age gap for participants with familial risk or developmental psychopathology (ADHD, anxiety)

<p float="left">
  <img src="figures/fhr_bag_sobp_distribution.png" style="width:45%; height:auto;"/>
  <img src="figures/adhd_bhrc_sobp_distribution.png" style="width:45%; height:auto;" /> 
  <img src="figures/anxiety_bag_sobp_distribution.png" style="width:45%; height:auto;" />
</p>


#### Results Presented at Society of Biological Psychiatry Conference in Toronto (April 2025)

<p float="left">
  <img src="figures/sobp_poster.png" style="width:100%; height:auto;"/>
</p>


#### Brain Age CNN Architecture 

![](figures/cnnvgg16.png)