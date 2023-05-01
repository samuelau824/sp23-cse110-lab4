1. The bug was that the numbers were being taken in as strings, and so the result 
   function simply concatenated the strings instead of finding their sum.
2. To fix the problem, I simply parsed the strings and made them into integers
   so that we would get the proper result.