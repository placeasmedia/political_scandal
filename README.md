# political_scandal

Replication Data for: THE ART OF SELF-CRITICISM: HOW AUTOCRATS PROPAGATE THEIR OWN POLITICAL SCANDALS

To be Unblocked, 2023, "Replication Data for: THE ART OF SELF-CRITICISM: HOW AUTOCRATS PROPAGATE THEIR OWN POLITICAL SCANDALS", To Be Inserted, Harvard Dataverse, DRAFT VERSION, UNF:6:BKpCBBvMZeTMvup9aSBHXg== [fileUNF] 

replication_code_PC_20230720.Rmd is the main R notebook file

sinanews_comments_analysis.csv and ac_synthetic_control_aggregated_by_day.csv are two .csv file for regression analysis

train_bert_ac.py employs a BERT model to train classifiers for corruption news and predict_acnews.py uses the model trained to predict unlabelled news into corruption/non-corruption news

sina_domesticnews_getnews.py and sina_get_comments.py are two files that can collect Sina News and its comments.

media_sources.csv contains more than 2,000 manually labelled media sources that appear on Sina News

sinaclick_news.csv contains all news articles used in the analysis

sinanews_comments.csv contains all news comments used in the analysis

pc_replication.backup is the backup file for a PostgreSQL database that has all the data

All the .sql files work with the PostgreSQL database
