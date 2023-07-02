# EDNet: Atention-Based Multimodal Representation for Classification of Twiter Users Related to Eating Disorders

This GitHub repository contains the benchmark dataset generated in our EDNet paper [1]. The dataset contains the details of four different types of Twitter users, categorised on the basis of the nature of their engagement with eating disorder (ED) related contents. The dataset statistics as given in the paper, is shown below. Here we share the complete *imbalanced* dataset. The balanced dataset can be created as a subset of this imbalanced version.

![image](https://github.com/tarique-ar/EDNet/assets/114371022/adc94229-cd50-4a73-8114-21ec58ffd50a)

Overall, the dataset contains the details about the annotated users, their entire tweet history and the associated tweet details. These details are simplified and curated in two csv files: *Users_EDNet_WWW2023.csv* and *Tweets_EDNet_WWW2023.csv*. The contents are completely anonymised to hide all kinds of individual/personal information (including IDs, names, usernames, @mentions, etc.), and cleaned to a great extent. 

+ *Users_EDNet_WWW2023.csv*: This file contains the user details. There are a total of 21477 rows, where each row (except the first) corresponds to a user, having a unique ID. There are a total of 12 columns. The first column is the unique *User ID*, the second column shows the biography as given in the corrsponding user profile, which is followed by 9 columns of user-level raw features (as provided by the Twitter API), and the last column shows the annotated label. The labels *ED*, *Healthcare*, *Communicator*, and *NonED* are used to denote an *ED user*, a *Healthcare professional*, a *Communicator*, and a *Non-ED user*, respectively.

+ *Tweets_EDNet_WWW2023.csv*: This file contains the tweet details. There are a total of 981301 rows, where each row (except the first) corresponds to a tweet having a unique ID. There are a total of 23 columns. The first column is *User ID* of the user (from *Users_EDNet_WWW2023.csv*) who has posted the corresponding tweet, the second column is its unique *Tweet ID*, the third column shows the actual tweet, and it is followed by 20 columns of tweet-level raw features (as provided by the Twitter API). 

#### References
[1] Mohammad Abuhassan, Tarique Anwar, Chengfei Liu, Hannah K. Jarman, Matthew Fuller-Tyszkiewicz, EDNet: Attention-Based Multimodal Representation for Classification of Twitter Users Related to Eating Disorders, Proceedings of The ACM Web Conference (WWW 2023), pages 4065-4074, 2023.

 
If you find our dataset/research useful, please consider citing our paper.
```
@inproceedings{abuhassanWWW2023,
  author       = {Mohammad Abuhassan and
                  Tarique Anwar and
                  Chengfei Liu and
                  Hannah K. Jarman and
                  Matthew Fuller{-}Tyszkiewicz},
  editor       = {Ying Ding and
                  Jie Tang and
                  Juan F. Sequeda and
                  Lora Aroyo and
                  Carlos Castillo and
                  Geert{-}Jan Houben},
  title        = {EDNet: Attention-Based Multimodal Representation for Classification
                  of Twitter Users Related to Eating Disorders},
  booktitle    = {Proceedings of the {ACM} Web Conference 2023, {WWW} 2023, Austin,
                  TX, USA, 30 April 2023 - 4 May 2023},
  pages        = {4065--4074},
  publisher    = {{ACM}},
  year         = {2023},
  url          = {https://doi.org/10.1145/3543507.3583863},
  doi          = {10.1145/3543507.3583863}
}
```

# Contact

[Mohammad Abuhassan](https://scholar.google.com/citations?user=eWbhAbMAAAAJ&hl=en), Swinburne University of Technology, Australia

[Tarique Anwar](https://www-users.york.ac.uk/~ta1114/), University of York, UK
