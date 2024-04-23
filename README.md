# Jhourney's jhana EEG dataset

This repostiry contains:
- Instructions how to download Jhourney's open dataset
- Paper draft, which covers in details how the dataset was collected
- A introductory notebook with main methods, that allow to access the data

What's coming soon:
- A preprocessed version of the dataset
- Code for the analysis of this data
- Paper describing the analysis

## Dataset access
This dataset is standardized according to the [BIDS](https://bids-specification.readthedocs.io/en/stable/) format and put online as raw as possible. Details on methodology, hardware, modalities etc. can be found in the paper draft and the dataset metadata files. 

To download the dataset simply use [this link](https://drive.google.com/drive/folders/1PM5lDLJr2LKleADL9zM65HOQY8ykYg2_?usp=drive_link).

If you need to download it using terminal, you can use `gdown` tool.

1. Run `pip install gdown` to install the tool
2. Run `gdown --folder 1PM5lDLJr2LKleADL9zM65HOQY8ykYg2_ -O /output/path` with specified output path.
