# Class project

In this repository, we aim to reproduce parts of 

Boehm, J. K., Williams, D. R., Rimm, E. B., Ry , C., & Kubzansky, L. D. (2013). Relation between Optimism
and Lipids in Midlife. The American Journal of Cardiology, 111(10), 1425-1431.
(http://doi.org/10.1016/j.amjcard.2013.01.292)

which can be downloaded [here](https://www.ajconline.org/article/S0002-9149(13)00388-3/pdf). The study investigates the relationship between
optimism and lipids.

In order to run our [notebook](class_project.Rmd), you can simply clone this repository: all required data are stored in `/data`. If you prefer to dowload the data yourself, we use the MIDUS II datasets. Check out [here](https://www.icpsr.umich.edu/web/ICPSR/studies/4652?archive=ICPSR&q=MIDUS+) for the survey results, and [here](https://www.icpsr.umich.edu/web/NACDA/studies/29282) for the biomarker data. 

The summary of our findings are the following:
- Overall, the paper provides reasonably good information about what they did in their analysis. However, they skip some important details and they don't provide their source code. 
- In their pre-processing, they selected 990 patients. We get 999. This means that the two ways of pre-processing are reasonably similar, but it is difficult to say where they are different as not enough information is provided in the paper. 
- We tried to reproduce Figure 1 in the paper. We get similar results to what they show in the paper (both the figure and the summary statistics), however they are not exactly equal. This could be due to the different pre-processing. 
