# Bigdata-PyFlink
Introduction to PyFlink and its examples


## Team- Members
<table>
<td align="center"><a href="https://github.com/sumana-reddy"><img src="https://avatars.githubusercontent.com/u/60016064?s=460&u=33898f8b8524f47cd6c76f8ecc4e022cdaa1c118&v=4" width="100px;" alt=""/><br /><sub><b>Sumana Reddy</b></sub></a><br /></td>

<td align="center"><a href="https://github.com/navyadevineni"><img src="https://avatars.githubusercontent.com/u/31991773?s=460&u=eafb1e0830d69219a585de9253b7e13a6a6cbece&v=4" width="100px;" alt=""/><br /><sub><b>Navya Devineni</b></sub></a><br /></td>  

<td align="center"><a href="https://github.com/Ravichanderreddy-goli"><img src="https://avatars.githubusercontent.com/u/60166223?s=460&u=c7fb963d9cc353dcb9f355a333aa551aacf9b4f1&v=4" width="100px;" alt=""/><br /><sub><b>Ravichander Reddy</b></sub></a><br /></td>

<td align="center"><a href="https://github.com/Krishna-Koyyalamudi"><img src="https://avatars.githubusercontent.com/u/60024842?s=460&u=94ef0e3e7234e941e6b5b7e3f08a5388ab5cef6f&v=4" width="100px;" alt=""/><br /><sub><b>Krishna Sumanth</b></sub></a><br /></td>

<td align="center"><a href="https://github.com/swaroopatirumalareddy"><img src="https://avatars.githubusercontent.com/u/60026979?s=400&u=6e0265503d7058525120ffe9609c70e751a633f0&v=4" width="100px;" alt=""/><br /><sub><b>Swaroopa Tirumalareddy</b></sub></a><br /></td>

<td align="center"><a href="https://github.com/Vishalreddy114"><img src="https://avatars.githubusercontent.com/u/59984658?s=400&u=6c8e72e6a6a75dbd8bddb92ecc54194b899e9855&v=4" width="100px;" alt=""/><br /><sub><b>Vishal Reddy </b></sub></a><br /></td>
</table>

## Data Sets
- https://www.kaggle.com/gregorut/videogamesales
- https://www.kaggle.com/shivamb/netflix-shows

## Introduction to PyFlink
- PyFlink is simply a combination of Apache Flink with Python, or rather Flink on Python.

## Subtopics
- [Krishna Sumanth Koyyalamudi](https://github.com/Krishna-Koyyalamudi) - Average time gap between the Movie/TV Show Released year and the year it is added to Netflix
- [Swaroopa Tirumalareddy](https://github.com/swaroopatirumalareddy) - At intial I would like perform operations that will give us the number of rows, memory usage, details about the columns and whether there are any null values, along with the type of data about my data set.
- [Ravichander Reddy Goli](https://github.com/Ravichanderreddy-goli) - To really understand what is going on in the data, we will need to see a distribution.I would like to perform this operation using Histogram
- [Vishal Reddy Vennavaram](https://github.com/Vishalreddy114) - I would like to perform various operations like word count on the csv file to by using pyflink.
- [Sumana Reddy Reddybathula](https://github.com/sumana-reddy) - I would like to perform scatter matrix to look how potentially the data is related to each other.
- [Navya Devineni](https://github.com/navyadevineni) - Worked on how to install [PyFlink](https://ci.apache.org/projects/flink/flink-docs-release-1.12/flinkDev/building.html#build-flink) and installed locally.

## Vid grid video links (Individual)
- Sumana: https://app.vidgrid.com/view/NImGtrKh8MAl
- Navya: https://app.vidgrid.com/view/l4nDyOWl3nKs
### Swaroopa Tirumalareddy

For this project, I have taken data set from kaggle.com  which contains the information regarding netflix movies and Tv shows. My Contribution in this project is I have performed some operations on dataset to get the basic information about the data set like displaying feature names of the dataset, fetching the details like the number of rows, memory usage, details about the columns and whether there are any null values, along with the type of data and  counting the number of different values in a single column specified and so on.
#### Prerequisites:
- Apache Flink
- python
- Colaboratory(Google Colab)(Colab allows us to write and execute Python in your browser, with Zero configuration required, Free access to GPUs and it is easy to share).
- A dataset to perform operations
#### Process and Commands:
1 First we need to open colab in a web browser then select new notebook  

2 We need install Apache Flink using the following command 

  - !pip install apache-flink
  
3 Once we get installing ApacheFlink, we need to import all neccesary libraies 

4 As per my operations, I have imported the following libraries 

   - from pyflink.table import StreamTableEnvironment, DataTypes, table_config 

   - from pyflink.datastream import StreamExecutionEnvironment

   - import pandas as pd

   - from pandas.plotting import scatter_matrix

5 After importing all the required libraries, upload your dataset into colab and start working on your project

### References:
- https://en.wikipedia.org/wiki/Apache_Flink
- https://colab.research.google.com/notebooks/intro.ipynb#recent=true
- https://flink.apache.org/2020/04/09/pyflink-udf-support-flink.html
 



