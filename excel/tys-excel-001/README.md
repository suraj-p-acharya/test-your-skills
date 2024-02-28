# Problem Statement
In this challenge we will write a formula to add (-) between Text and Number

Formula used

1	FIND

2	IFERROR

3	SMALL

4	REPLACE

But this can be solved using combination of other formulas as well, as every problem will have more then one solutions



# Download the files TYS_Excel_001

We have Text and number in Column B below, Our job is to Write a Excel Formula to separate it and add (-) between Text and Number.


![image](https://github.com/suraj-p-acharya/test-your-skills/assets/118610857/59eaa2e4-9a9f-4813-980e-b31f0593f118)

# Formula Used

=REPLACE(B3,SMALL(IFERROR(FIND($G$1:$G$10,B3),""),1),0,"-")
