# Horse_race_big_data_derby_2022

Dataset: https://www.kaggle.com/competitions/big-data-derby-2022/overview

# Goal of the Competition

The goal of this competition is to analyze horse racing tactics, drafting strategies, and path efficiency. You will develop a model using never-before-released coordinate data along with basic race information.

Your work will help racing horse owners, trainers, and veterinarians better understand how equine performance and welfare fit together. With better data analysis, equine welfare could significantly improve.

# nyra_2019_complete.csv - 
This file is the combined 3 files into one table. The keys to join them trakus with race - track_id, race_date, race_number. To join trakus with start - track_id, race_date, race_number, program_number.

    track_id - char(3)
    race_date - date
    race_number - char(3)
    program_number - char(3)
    trakus_index - int
    latitude - float
    longitude - float
    distance_id - int
    course_type - char(1)
    track_condition - char(3)
    run_up_distance - int
    race_type - char(5)
    post_time - char(5)
    weight_carried - int
    jockey - char(50)
    odds - int
    position_at_finish - An integer of the horse's finishing position.
