# Quine_McCluskey
C Program for implementation of tabulation method.


Tabulation method is used for function minimization from the given minterms of a function. This method is generally used for function of more than 5 or 6 variables (which is when minimization with the help of k-maps becomes very difficult. This program takes the input minterms for a functions and then performs calculations for pairing minterms in different columns and then uses the resultant prime implicants to find the minimized function with the help of the prime implicants table. All the columns with the pairings as well as the prime implicants table are dislayed. Also static memory allocation is used, thus the program may not work above a certain value(if needed for higher values more memory can be allocated or memory may be allocated dynamically). This is not the best possible solution but can be further optimized by reducing the time and space complexity. Any improvements in program are more than welcome. 

(Note :- Don't care conditions are not included but can be easily added by modifying a few functions, click here to know how don't care conditions are used in tabulation method).
