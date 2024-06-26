### High-School-ML-Tutorial

A simple ML tutorial for RNA-seq analysis (A high-school tutorial)

#### Dataset

Download the dataset and save it to the `data/` directory:

```shell
cd ./data
wget https://archive.ics.uci.edu/static/public/401/gene+expression+cancer+rna+seq.zip
unzip gene+expression+cancer+rna+seq.zip
tar -xvf TCGA-PANCAN-HiSeq-801x20531.tar.gz
```

After the last command, you will see a directory `./data/TCGA-PANCAN-HiSeq-801x20531/`, within which there
will be two files:

```shell
-rw-rw-r-- 1 dash dash     12713 May 23  2016 labels.csv
-rw-rw-r-- 1 dash dash 206186150 May 23  2016 data.csv
```


#### Machine Learning

We will be first using t-SNE to visualise this dataset. Then, we will use an ensemble machine learning technique to classify the samples.

 - t-SNE Notebook: [t-SNE](t-SNE-GenEx.ipynb)
 - Random Forest: [RF](RF.ipynb)
 
#### Further reading

 - [Wiki: Random Forest](https://en.wikipedia.org/wiki/Random_forest)

