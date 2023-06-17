There are 2 types of wide_song_data in this notebook

wide_song_data_sparse: used for building up recommend model
wide_song_data: used for creating wide_song_data_sparse, and the recommendation model needs it to generate recommendation song

When updating the Python project, just copy the "song_play_record.csv" and "knn_model.sav" into 

recommenders\collaborative_filtering\dataset for song_play_record.csv
recommenders\collaborative_filtering\model for knn_model.sav