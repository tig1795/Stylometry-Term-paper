Comparison of different clustering methods regarding the possibility to cluster songs into genres based 
only on their lyrics for the course "Stylometry" of the Julius-Maximilians-University, WS 19/20.

The data set and the various clustering procedures are divided into folders and structured as follows:

Literatur

    HC: hier werden die Beziehungen zwischen den Genres und Künstlern beschrieben, 
        die für die Erklärung der Ausreißer benötigt wurden
    Visualization_in_Stylometry
    Topic-modelling-with-scikitlearn

datasets

This folder contains the old and the new record.

    Currently_dataset
        song_decades_long.csv
    Old_datasets
        Datenexploration_1
            pop_genre1_2.csv
            rock_genre1_2.csv
            sample_25percent.csv
            songs_longtexts.csv
            songtexte_bereinigt_gekuerzt.csv
        Datenexploration_2
            songs_100.csv
            songs_25.xlsx
        Discogs
            discogs_dates.xlsx
            discogs_id.xlsx
        Spotify
            songdata.csv
            songdata.xlsx
            songs_decades.csv
            songs_plus_dates.csv
    datasets_info

Images

    Finale_Bilder
        AutoEncoder
            Results
        Delta
            Results
        GMM
            Results
        HC
            Results
        SVM
            Results
        TopicModelling
            Results
        lda.html
        preprocessing
        type_token
        wordcoluds
    Dataexploration_1
        1_number_of_songs
        2_wordsclouds
            wordclouds_by_artist
            wordclouds_by_genre
        3_number_of_words
        5_type_token
        6_length_of_songs
        song_decades_long
    Dataexploration_2
        2_Visualisierung
            Genres
        3_common_words
            POS
            text
    Dimensionsreduktion
        PCA
            MDS
        T-SNE
            song_decades_long
        UMAP
    GMM
        song_decades_long
    HC
        song_decades_long
    K-Means/K_Means
        1_K-Means -- versch. Implementierungen
        2_K-Means -- minibatch
        3_K-Means -- Genres
            song_decades_long- Genres
        4_K-Means -- gif
        5_K-Means --decades
    Preprocessing

Notebooks

    .ipynb_checkpoints
    0_preprocessing
    1_KMeans
        Dimensionsreduktion
            umap
        Implementierung_K-Means
        K_Means
    2_SVM
        SVM_KM
    3_HC
    4_GMM
    5_DBScan
    6_TopicModeling
        mallet_text
    7_AutoEncoder
        Final AutoEncoder
    8_Delta
        zscores
    Clustering_Verfahren .ipynb - Pipeline for all procedures

-.gitattributes

-README.md

