Ahmed Hussain Syed- 2273474
Computer Architecture (Dr. Weidong Shi)
----------------------------------------------

ReadME File for the assignment:

The attached code by the name "branch_prediction" in C++ demonstrates branch prediction by using a conditional branch on a sorted and unsorted data and later, replaces the branch with a bitwise operation.

The exact time will vary depending on the hardware infrastructure but the relative values will be the same.

- We can make the following key observations:

- Time taken for code with the conditional branch with sorted data is nearly half that of with unsorted or random data. This is because of branch prediction.

- Time taken for code with bitwise operation with sorted data and unsorted / random data is nearly same. Branch prediction does not play any role in this case.

- Time taken for code with bitwise operation is slightly more than the code with conditional branch and sorted data.

When the data is completely random, the branch predictor is rendered useless because it cannot predict random data. Thus, there will be around 50% misprediction.