# Database Reasoning over Text with Wikipedia Table Data

This repository contains the code for running inferences on trained model



## Data

The dataset includes entity names from Wikidata. 
This dataset includes sentences from the KELM corpus enriched with Table data from Wikipedia.


## Repository Structure
The repository is structured in 6 sub-folders:

* 5k_data has original KELM data fo 5 thousand triples. This folder has 3 files `balanced_rain`, `balanced_dev` and `balanced_test`.This folder has a subfolder `Model_Data` which contains all the trained model data. Download the [Model File from here](https://drive.google.com/file/d/1Fqp8Xi_BWdVSUmAthYA1c3IAvVq3NFw8/view?usp=sharing). This folder has 3 files `balanced_rain`, `balanced_dev` and `balanced_test`.Move this file in `Model_Data` folder.
* Inference_5k_datatable has original KELM data with Wikipedia table fo 5.67 thousand triples. This folder has 3 files `balanced_rain`, `balanced_dev`, `balanced_test` and `combined_data`. This folder has a subfolder `Model_Data` which contains all the trained model data. Copy the pytorch_model.bin file from [5k_data/Model_data](5k_data/Model_data/).
* Inference_original_onlytable has Wikipedia table fo 677 triples. This folder has 3 files `balanced_rain`, `balanced_dev`, `balanced_test` and `combined_data`. This folder has a subfolder `Model_Data` which contains all the trained model data. Copy the pytorch_model.bin file from [5k_data/Model_data](5k_data/Model_data/).
* 5k_datatable has original KELM data with Wikipedia table fo 5.67 thousand triples. This folder has 3 files `balanced_rain`, `balanced_dev` and `balanced_test`. This folder has a subfolder `Model_Data` which contains all the trained model data. Download the [Model File from here](https://drive.google.com/file/d/1cO7F0asv0ar9i176Q9St832y1P8epQBu/view?usp=sharing). This folder has 3 files `balanced_rain`, `balanced_dev` and `balanced_test`. Move this file in `Model_Data` folder.
* Inference_orig+table_onlytable has Wikipedia table fo 677 triples. This folder has 3 files `balanced_rain`, `balanced_dev`, `balanced_test` and `combined_data`. This folder has a subfolder `Model_Data` which contains all the trained model data. Copy the pytorch_model.bin file from [5k_datatable/Model_data](5k_datatable/Model_data/).
* onlytable has Wikipedia table fo 677 triples. This folder has 3 files `balanced_rain`, `balanced_dev` and `balanced_test`. This folder has a subfolder `Model_Data` which contains all the trained model data. Download the [Model File from here](https://drive.google.com/file/d/1Dzq8zKncBFEWB4WgGUzV6_xTste7x3Un/view?usp=sharing). Move this file in `Model_Data` folder.



## Setup

Install the necessary packages by running a pip install:

```
pip3 install -r requirements.txt
```
Download the repository and have the same repository structure as mentioned above.
Run the `Data_Statistics.ipynb` which will setup the enivronment and produce the statistics.
Run the `Spreadsheet.ipynb` which will generate a spreadsheet of all input, correct output and system output for each inference.





