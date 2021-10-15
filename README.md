# School_District_Analysis

## Overview

The purpose of this analysis was to show how the districts testing results changed by excluding the Thomas High School(THS) 9th grade student results.  

## Results

### How is the district summary affected?
- At a summarized level of Charter vs District schools the exclusion of THS 9th graders had minimal impact on the Districts overall scores:

  **With THS**
  
     ![image](https://user-images.githubusercontent.com/90879042/137406413-90dc8a80-9767-41dc-847e-bf127bb3babf.png)
  
     ![image](https://user-images.githubusercontent.com/90879042/137406774-e063e286-95cf-4a36-a65c-5b97ebbfb18a.png)

  
  
  **Without THS**
  
  ![image](https://user-images.githubusercontent.com/90879042/137406424-4bd1db30-ada8-49ea-a754-2ace24f37e1f.png)
  
  ![image](https://user-images.githubusercontent.com/90879042/137406787-2cca0f1f-522a-473b-955a-4a4ed8fff442.png)


### How is the school summary affected?
- When looking at how the school summary is affected, the only change will be in regards to THS where the overall passing percentage dropped by 0.3percentage points. 


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- The impact of removing the ninth graders is rather minimal when comparing to other schools given the impact was only 0.3ppts difference overall.  

### How does replacing the ninth-grade scores affect the following:


**- Math and reading scores by grade**

   - The 9th grade scores for THS in both math and reading were replaced with NaN.
    
   ![image](https://user-images.githubusercontent.com/90879042/137423354-d79bd7ee-440b-4aae-a4a2-73deddc9fb12.png)![image](https://user-images.githubusercontent.com/90879042/137423416-ea5b6baf-3959-486b-9ad7-e3c32376244f.png)

**- Scores by school spending**

   - Similar to the district summary, in order to see an impact you need to look at the un-formatted summary:
    
   **With THS**
   
   ![image](https://user-images.githubusercontent.com/90879042/137423860-907eb7f4-3e9e-44f5-bfe7-f2c88a96e7bc.png)
     
   **Without THS**
   
   ![image](https://user-images.githubusercontent.com/90879042/137423907-a7ec855f-e739-4dd4-a7c2-9a40bbf03cec.png)    

**- Scores by school size**

   - Common theme- in order to see an impact you need to look at the un-formatted summary:
    
   **With THS**
   
   ![image](https://user-images.githubusercontent.com/90879042/137424329-a3d60e80-5367-48c2-8415-e98ac62afa06.png)
     
   **Without THS**
   
   ![image](https://user-images.githubusercontent.com/90879042/137424284-1d410690-8ce4-4bf5-b197-8c737a8bb53a.png)


**- Scores by school type**

   - Again, in order to see an impact you need to look at the un-formatted summary:
    
   **With THS**
   
   ![image](https://user-images.githubusercontent.com/90879042/137424513-73faa5e9-6e72-42f3-8d94-84c61564abce.png)
     
   **Without THS**
   
   ![image](https://user-images.githubusercontent.com/90879042/137424457-f9d7ba7b-7402-4624-b9a7-790e581b2fb6.png)


## Summary

To summarize the impact of removing the 9th grade THS class - the impact was very minimal:
  - Overall % Passing for a charter school went from 90.43% to 90.39%
  - Overall % Passing for a medium size school went from 90.62% to 90.56%
  - Overall % Passing for schools spending $630-644 per Student went from 62.86% to 62.78%
  - Overall % passing for THS went from 90.95% to 90.63%
