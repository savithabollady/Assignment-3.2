1. Define matrix mymat by replicating the sequence 1:5 for 4 times and transforming into a matrix, sum over rows and columns.

> mymat<-matrix(rep(seq(5), 4), ncol = 5)
> # mymat sum on rows
> apply(mymat, 1, sum)
[1] 15 15 15 15
# mymat sum on columns
> apply(mymat, 2, sum)
[1] 10 11 12 13 14
