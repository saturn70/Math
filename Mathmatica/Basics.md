### Range
#### Range[3]   # Output -  {1,2,3} 
#### Range[5,10] # Output - {5,6,7,8,9,10}
### NestList
#### NestList[f,expr,n]
#### gives a list of the results of applying f to expr 0 through n times.

### Nest[(1 + #)^2 &, 1, 3]
#### starting value - 1
#### number of apply - 3
( 1 + 1 ) ^ 2 = 4 
( 1 + 4 ) ^ 2 = 25
( 1 + 25 ) ^ 2 = 676 

#### Nest[(1 - #)^3 & ,2, 2]
#### starting value - 2
#### number of apply - 2
( 1 - 2 ) ^ 3 = -1 
( 1 - ( - 1 )) ^ 3 = 8
