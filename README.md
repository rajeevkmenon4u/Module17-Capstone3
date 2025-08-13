# Module17-Capstone3
Comparing Classifiers
## Brief summary 
Overview: Goal is to compare the performance of the classifiers namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. We will utilize a dataset related to marketing bank products over the telephone.
## Problem Statement
This research focus on targeting through telemarketing phone calls to sell long-term deposits. Within a campaign, the human agents execute phone calls to a list of clients to sell the deposit (outbound) or, if meanwhile the client calls the contact-center for any other reason, he is asked to subscribe the deposit (inbound). Thus, the result is a binary unsuccessful or successful contact.
## Business Objective
Business objective is to automatically predict the result of a phone call to sell long term deposits. 
## Data Analysis
   ###### Analysing the data and identfying the anamolies
   By looking at the column 'Y' 
    + No---:88.73
    + yes ---:11.27
   #####  This clearly indicates the dataset provided is not balanced 
   <img width="531" height="265" alt="image" src="https://github.com/user-attachments/assets/6ffb5aaa-dd4d-41e0-9ceb-ffe74c897c75" />
   
   #####  Two columns Pdays & duration felt some significance. Will these columns make the data Balanced ( Pdays Column )
   <img width="1547" height="775" alt="image" src="https://github.com/user-attachments/assets/923bf570-6f80-45f1-87ac-beeaaec53c9c" />
   <img width="767" height="612" alt="image" src="https://github.com/user-attachments/assets/419462e4-4e49-4d9e-b189-f0a700929708" />
   
## Decision based on EDA
   1. For the whole dataset (it is 89% to 11%) 
   2. Where as after considering the column "pdays not equal 999", the dataset gets better balaced with the ratio on (64% to 35%)  
   3. Decision to perfom model comparison with the small dataset first and then whole dataset.
   
## Four Model Results with pdays not equal 999

   <img width="1496" height="597" alt="image" src="https://github.com/user-attachments/assets/193ac7c2-4933-4cd0-b26b-6f425fc335d7" />
   #### Based on the above results below are the findings for the unbalced dataset
   #### In this case Decision tree is giving the best F1 score, Preciosn & Recall also looks good 
   #### SVM has the good recall but from the time execution it is much longer then Decison Tree
   
## Four Model Results with pdays not equal 999

<img width="1353" height="715" alt="image" src="https://github.com/user-attachments/assets/62621fff-5f22-44ba-9e86-f604f4b433c2" />

