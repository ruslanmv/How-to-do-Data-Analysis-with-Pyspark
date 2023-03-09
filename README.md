## Data Analysis in Pyspark

Hello today we are going to discuss how to perform data analysis of one dataset by using pyspark.



## Step 1. Installation of Conda

First you need to install anaconda at this [link](https://www.anaconda.com/products/individual)

![png](assets/images/posts/README/1-16601652164621.jpg)

in this location **C:\Anaconda3** , then you, check that your terminal , recognize **conda**

```
C:\conda --version
conda 23.1.0
```

## Step 2. Environment creation

The environments supported that I will consider is Python 3.10,

I will create an environment called **analysis**, but you can put the name that you like.

```
conda create -n analysis python==3.10
```

then we activate

```
conda activate analysis
```

then in your terminal type the following commands:

```
conda install ipykernel notebook
```

then

```
python -m ipykernel install --user --name analysis --display-name "Python (Analysis)"
```

then we install the following libraries used to the data analysis

```
pip install wget seaborn matplotlib requests tqdm
```

If you are in colab

```
pip install pyspark and go to the step 3
```

