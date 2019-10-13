## MSB1015 Assignment 2
Welcome to the repository of MSB1015 Assignment 2! Here I keep track of my progress of MSB1015 2019 Assignment 2 at Maastricht University.

## Project Description
Chemical properties, such as the boiling point, can be derived from the structure of a chemical compound. In 1947, Harry Wiener already made a correlation model to link structural features to boiling points (ref1). The idea to use mathematical models to predict chemical properties from compound structures has been expaned since then. 

In this project I use a SPARQL query to obtain the smiles and boiling points of simple alkanes from WikiData (ref2). I use the smiles to get descriptors from the chemical development kit (CDK) database (ref3-6). These descriptors contain information on the structural properties of the alkanes (see section 2 for more details). Finally, I train a Partial Least Squares (PLS) model to predict these properties from the chemical properties of the compounds and plot the results. 

## Files
MSB1015_Assignment2_SuzannetenHage.rmd <- Code in Interactive R Markdown Notebook. 

## Installation
**JAVA** <br/>
The rJava package requires Java to be installed. The code has been developed using Java version 1.8.0_191. A tutorial on how to install this Java Version on windows can be found [here](https://downlinko.com/download-install-jdk-8-windows.html). 

**Required R packages:** <br/>
The project requires several packages. The code checks automatically for missing packages and installs them. The required packages are: <br/> 
* WikidataQuery 
* rJava
* rcdk
* stringi
* caTools
* pls
* Metrics

## Authors
Suzanne ten Hage

## Additional Information <br/>
Please note that this project is released with a Contributor Code of Conduct. By participating in this project you agree to abide by its terms.

## Sources
1. Wiener H. Structural Determination of Paraffin Boiling Points. Journal of the
American Chemical Society. 1947 Jan;69(1):17–20.
ref2: https://www.wikidata.org/wiki/Wikidata:Main_Page (12-10-2019)
ref3: Willighagen et al. The Chemistry Development Kit (CDK) v2.0: atom typing, depiction, molecular formulas, and substructure searching. J. Cheminform. 2017; 9(3), doi:10.1186/s13321-017-0220-4
ref4: May and Steinbeck. Efficient ring perception for the Chemistry Development Kit. J. Cheminform. 2014, doi:10.1186/1758-2946-6-3
ref5: Steinbeck et al. Recent Developments of the Chemistry Development Kit (CDK) - An Open-Source Java Library for Chemo- and Bioinformatics. Curr. Pharm. Des. 2006; 12(17):2111-2120, doi:10.2174/138161206777585274
ref6: Steinbeck et al. The Chemistry Development Kit (CDK): An Open-Source Java Library for Chemo- and Bioinformatics. J. Chem. Inf. Comput. Sci. 2003 Mar-Apr; 43(2):493-500, doi:10.1021/ci025584y
