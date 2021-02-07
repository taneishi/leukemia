# [Leukemia dataset](https://web.stanford.edu/~hastie/CASI_files/DATA/leukemia.html)

Gene expression measurements on 72 leukemia patients, 47 "ALL" (see section 1.2), 25 "AML".
These data arise from the landmark Golub et al (1999) Science paper.

There is a larger set consisting of 7128 genes.
It is stored as the 7128 x 72 matrix (10MB) leukemia_big.csv, with the column names denoting the class labels.

There is also a smaller subset of these data, consisting of 3571 genes, used in Section 19.1.
It is stored as the 3571 x 72 matrix (5MB) leukemia_small.csv, with again the column names denoting the class labels.

Disclaimer: these data come with a data analysis challenge.
The columns of the two datasets are in different order.
Furthermore, the genes in the big dataset have been transformed, with the exact transformation used lost in time.
We also do not know the correspondence between the 3157 and 7128 genes.
