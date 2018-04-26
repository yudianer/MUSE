when using used a small epoch size (and consequently more epochs), 
the evaluations are more frequent, and you are more likely to get a good model.


Parameter specification:
#### 1.we will never consider pairs of words where you have a source word or a target word which is not in the top 15000 most frequent words
--dico_max_rank 15000  

#### 2.we will never consider more than 10000 pairs in total
--dico_max_size 10000  

#### 3.that we will always consider at least 1000 pairs (used in combination with dico_threshold that removes translations for which we do not have a high confidence)
--dico_min_size 1000   


