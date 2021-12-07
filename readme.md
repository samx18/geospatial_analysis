
# Getting Started with Geospatial Data Analysis

This is the code repository for the blog post [Getting Started With Geospatial Analysis on SageMaker Studio Lab](https://towardsdatascience.com/getting-started-with-geospatial-analysis-b2116c50308b).

![Lake Shasta](https://github.com/samx18/geospatial_analysis/blob/main/images/lake_shasta.png)

## Data

The datasets used are publicly available geographic datasets and then explore the sentinel geospatial dataset available at AWS open data registry. The examples cover California Lakes and Counties using geographic vector data and then focus Lake Shasta in California for analyzing Sentinel-2 geospatial data and calculating spectral indices.

- The CA Counties dataset contains boundaries for CA State, counties and places from the US Census Bureau's 2016 MAF/TIGER database available [here](https://data.ca.gov/dataset/ca-geographic-boundaries).
- The California water bodies dataset is published by California. Department of Fish and Game. Marine Resources Region and is available for download [here](https://maps.princeton.edu/download/file/stanford-zx543xm6802-shapefile.zip).
- The Sentinel-2 dataset is available publicly at the [AWS open data registry](https://registry.opendata.aws/sentinel-2/).

## Prerequisites

- A SageMaker Studio Lab account
- A Free Tier AWS account (For keys to download data from S3)
- A free Sentinel Hub account 

## Environment

Creating a environment in Studio Lab is easy, just go to your cloned directory and select the environment.yml file (or upload it directly from the repository), right click the YAML file and select create environment. This will create new Studio Lab environment with all the required packages needed. You can then open `geospatial_analysis` notebook in the newly created kernel.

Optionally you can also uncomment the package installation section of the notebook to install these packages manually.
