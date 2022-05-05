# Repository of the key data sets used in *Reading The Bazaar: Comparing Approaches in the Classification of Linux C Function Parameter Mutability*

This repository contains the two primary data sets used in the investigation and comparison of different labeling approaches for \
labeling Linux C parameter immutability. Code and nebulous data associated with data set generation can be found at [this Github repository](https://github.com/mjgaughan/bz_func_declarations).
Code associated with machine learning modelling can be found at [this Github repository](https://github.com/mjgaughan/bz_models). Both repositories are \
unorganized. The human labeling interface can be found at [this Github repository](https://github.com/mjgaughan/flask-label-ui).

## The General Data Set

The general data set consists of a scraped list of 125k Linux parameters from the kernel data set. A range of information was included about them, \
including their parent function body. Due to the size of this data set (110MB), this data set was split in two for storage purposes.

## The Human Data Set

This data set consists of the 48 parameters shown to human survey respondents for mutability classification. 
