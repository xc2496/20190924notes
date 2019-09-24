# 20190924notes
In class notes
#Big names these days
#*New Schools venture Fund---Non-profit Organization
#more likely a agoverbment agency.

#Matrix VS Data Frame
#Create Matrix
#matrix()
#as.matrix
#Transpose Function (in assignment2)
#t()
#Diagonal Function
#diag()
#Replace or extract the diagonal of a matrix
#Matrix Multoplication
#%*%--Multiply two matrix together
#will be useful when we get to social network analysis


#Activity
#Create a data frame called A of three variables, each having three values
A<-data.frame("Name" = c(2,6,9), "Animal" = c(12,45,32), "number" = c(2,3,5))
A
#Convert the data frame to a matrix called B
B<-as.matrix(A)
B
#Create a matrix called C that is the transposition of A
C<-t(A)
C
#Create a matrix called D that is the multiplication of C and B
D<-C%*%B
D
#Replace the diagonal values in D with missing values
diag(D)<-NA
diag(D)
D

 
 