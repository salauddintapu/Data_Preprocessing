# Data_Preprocessing
Includes data preprocessing steps, merging dataframes, PCA analysis, data distribution visualization (demonstarted using 3 columns & box plot). The dataset is collected from **Kaggle**. The dataset is split into train and test files into .csv format. I have merged both .csv files to perform preprocessing tasks. Handling **duplicate** and **null** values are basic steps. At first I have removed duplicates and null values but later on imputation methods has been introduced to remove missing values. **KNNImputer** is used to perform the task. <br>
**PCA Analysis** is dimensionality reduction technique and I reduced the dimensionality into 3D. <br>

**Dataset Link:** https://www.kaggle.com/datasets/salauddintapu/house-prices-advanced-regression-techniques
<br>
## image2csv.ipynb
This ipynb file is for image preprocessing step. It can will read all the image files of a given directory. Initially the file will store the folder name and image name into two different lists and after doing so, it will create a python dictionary using these lists and finally a pandas dataframe. After creating a df, the images will be encoded acording to the folder label using LabelEncoder. And in the end, the program will provide a csv file containg all these informations.
