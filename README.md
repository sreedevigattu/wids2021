
# WiDS Datathon 2021

- [WiDS Women in Data Science (WiDS) Datathon 2021](https://www.kaggle.com/c/widsdatathon2021)
The WiDS Datathon 2021 focuses on patient health, with an emphasis on the chronic condition of diabetes, through data from MIT’s GOSSIS (Global Open Source Severity of Illness Score) initiative. Brought to you by the WiDS Worldwide team at Stanford, the West Big Data Innovation Hub, and the WiDS Datathon Committee, this year’s datathon is open until March 1, 2021. Winners will be announced at the WiDS Conference via livestream, reaching a community of 100,000+ data enthusiasts across more than 85 countries.

- [Submission](https://www.kaggle.com/competitions/widsdatathon2021/leaderboard?search=theDataReaders)

# Environment

brew install libomp

# wids2021 dataset

columns                  , total   , nan_rows, %    
age                      ,   125169,     4988, 3.83
bmi                      ,   125667,     4490, 3.45
ethnicity                ,   128570,     1587, 1.22
gender                   ,   130091,       66, 0.05
height                   ,   128080,     2077, 1.60
hospital_admit_source    ,    96959,    33198, 25.51
icu_admit_source         ,   129917,      240, 0.18
weight                   ,   126694,     3463, 2.66
albumin_apache           ,    51994,    78163, 60.05
apache_2_diagnosis       ,   128472,     1685, 1.29
apache_3j_diagnosis      ,   129292,      865, 0.66
bilirubin_apache         ,    47597,    82560, 63.43
bun_apache               ,   104746,    25411, 19.52
creatinine_apache        ,   105275,    24882, 19.12
fio2_apache              ,    30437,    99720, 76.62
gcs_eyes_apache          ,   127967,     2190, 1.68
gcs_motor_apache         ,   127967,     2190, 1.68
gcs_unable_apache        ,   129448,      709, 0.54
gcs_verbal_apache        ,   127967,     2190, 1.68
glucose_apache           ,   115461,    14696, 11.29
heart_rate_apache        ,   129848,      309, 0.24
hematocrit_apache        ,   103399,    26758, 20.56
map_apache               ,   129737,      420, 0.32
paco2_apache             ,    30437,    99720, 76.62
paco2_for_ph_apache      ,    30437,    99720, 76.62
pao2_apache              ,    30437,    99720, 76.62
ph_apache                ,    30437,    99720, 76.62
resprate_apache          ,   129349,      808, 0.62
sodium_apache            ,   105638,    24519, 18.84
temp_apache              ,   123546,     6611, 5.08
urineoutput_apache       ,    66990,    63167, 48.53
wbc_apache               ,   100682,    29475, 22.65
d1_diasbp_invasive_max   ,    35089,    95068, 73.04
d1_diasbp_invasive_min   ,    35089,    95068, 73.04
d1_diasbp_max            ,   129880,      277, 0.21
d1_diasbp_min            ,   129880,      277, 0.21
d1_diasbp_noninvasive_max,   128521,     1636, 1.26
d1_diasbp_noninvasive_min,   128521,     1636, 1.26
d1_heartrate_max         ,   129895,      262, 0.20
d1_heartrate_min         ,   129895,      262, 0.20
d1_mbp_invasive_max      ,    35289,    94868, 72.89
d1_mbp_invasive_min      ,    35289,    94868, 72.89
d1_mbp_max               ,   129830,      327, 0.25
d1_mbp_min               ,   129830,      327, 0.25
d1_mbp_noninvasive_max   ,   127929,     2228, 1.71
d1_mbp_noninvasive_min   ,   127929,     2228, 1.71
d1_resprate_max          ,   129474,      683, 0.52
d1_resprate_min          ,   129474,      683, 0.52
d1_spo2_max              ,   129625,      532, 0.41
d1_spo2_min              ,   129625,      532, 0.41
d1_sysbp_invasive_max    ,    35119,    95038, 73.02
d1_sysbp_invasive_min    ,    35119,    95038, 73.02
d1_sysbp_max             ,   129886,      271, 0.21
d1_sysbp_min             ,   129886,      271, 0.21
d1_sysbp_noninvasive_max ,   128534,     1623, 1.25
d1_sysbp_noninvasive_min ,   128534,     1623, 1.25
d1_temp_max              ,   125663,     4494, 3.45
d1_temp_min              ,   125663,     4494, 3.45
h1_diasbp_invasive_max   ,    25328,   104829, 80.54
h1_diasbp_invasive_min   ,    25328,   104829, 80.54
h1_diasbp_max            ,   124630,     5527, 4.25
h1_diasbp_min            ,   124630,     5527, 4.25
h1_diasbp_noninvasive_max,   118818,    11339, 8.71
h1_diasbp_noninvasive_min,   118818,    11339, 8.71
h1_heartrate_max         ,   126083,     4074, 3.13
h1_heartrate_min         ,   126083,     4074, 3.13
h1_mbp_invasive_max      ,    25391,   104766, 80.49
h1_mbp_invasive_min      ,    25391,   104766, 80.49
h1_mbp_max               ,   123627,     6530, 5.02
h1_mbp_min               ,   123627,     6530, 5.02
h1_mbp_noninvasive_max   ,   116860,    13297, 10.22
h1_mbp_noninvasive_min   ,   116860,    13297, 10.22
h1_resprate_max          ,   123703,     6454, 4.96
h1_resprate_min          ,   123703,     6454, 4.96
h1_spo2_max              ,   123915,     6242, 4.80
h1_spo2_min              ,   123915,     6242, 4.80
h1_sysbp_invasive_max    ,    25350,   104807, 80.52
h1_sysbp_invasive_min    ,    25350,   104807, 80.52
h1_sysbp_max             ,   124638,     5519, 4.24
h1_sysbp_min             ,   124638,     5519, 4.24
h1_sysbp_noninvasive_max ,   118827,    11330, 8.70
h1_sysbp_noninvasive_min ,   118827,    11330, 8.70
h1_temp_max              ,   100454,    29703, 22.82
h1_temp_min              ,   100454,    29703, 22.82
d1_albumin_max           ,    58751,    71406, 54.86
d1_albumin_min           ,    58751,    71406, 54.86
d1_bilirubin_max         ,    53422,    76735, 58.96
d1_bilirubin_min         ,    53422,    76735, 58.96
d1_bun_max               ,   116423,    13734, 10.55
d1_bun_min               ,   116423,    13734, 10.55
d1_calcium_max           ,   113465,    16692, 12.82
d1_calcium_min           ,   113465,    16692, 12.82
d1_creatinine_max        ,   116884,    13273, 10.20
d1_creatinine_min        ,   116884,    13273, 10.20
d1_glucose_max           ,   121914,     8243, 6.33
d1_glucose_min           ,   121914,     8243, 6.33
d1_hco3_max              ,   110110,    20047, 15.40
d1_hco3_min              ,   110110,    20047, 15.40
d1_hemaglobin_max        ,   113925,    16232, 12.47
d1_hemaglobin_min        ,   113925,    16232, 12.47
d1_hematocrit_max        ,   114569,    15588, 11.98
d1_hematocrit_min        ,   114569,    15588, 11.98
d1_inr_max               ,    48944,    81213, 62.40
d1_inr_min               ,    48944,    81213, 62.40
d1_lactate_max           ,    34654,    95503, 73.38
d1_lactate_min           ,    34654,    95503, 73.38
d1_platelets_max         ,   111600,    18557, 14.26
d1_platelets_min         ,   111600,    18557, 14.26
d1_potassium_max         ,   117611,    12546, 9.64
d1_potassium_min         ,   117611,    12546, 9.64
d1_sodium_max            ,   116887,    13270, 10.20
d1_sodium_min            ,   116887,    13270, 10.20
d1_wbc_max               ,   112728,    17429, 13.39
d1_wbc_min               ,   112728,    17429, 13.39
h1_albumin_max           ,    11152,   119005, 91.43
h1_albumin_min           ,    11152,   119005, 91.43
h1_bilirubin_max         ,    10296,   119861, 92.09
h1_bilirubin_min         ,    10296,   119861, 92.09
h1_bun_max               ,    25167,   104990, 80.66
h1_bun_min               ,    25167,   104990, 80.66
h1_calcium_max           ,    24236,   105921, 81.38
h1_calcium_min           ,    24236,   105921, 81.38
h1_creatinine_max        ,    25373,   104784, 80.51
h1_creatinine_min        ,    25373,   104784, 80.51
h1_glucose_max           ,    55084,    75073, 57.68
h1_glucose_min           ,    55084,    75073, 57.68
h1_hco3_max              ,    23762,   106395, 81.74
h1_hco3_min              ,    23762,   106395, 81.74
h1_hemaglobin_max        ,    27367,   102790, 78.97
h1_hemaglobin_min        ,    27367,   102790, 78.97
h1_hematocrit_max        ,    27201,   102956, 79.10
h1_hematocrit_min        ,    27201,   102956, 79.10
h1_inr_max               ,    48944,    81213, 62.40
h1_inr_min               ,    48944,    81213, 62.40
h1_lactate_max           ,    11690,   118467, 91.02
h1_lactate_min           ,    11690,   118467, 91.02
h1_platelets_max         ,    24428,   105729, 81.23
h1_platelets_min         ,    24428,   105729, 81.23
h1_potassium_max         ,    29336,   100821, 77.46
h1_potassium_min         ,    29336,   100821, 77.46
h1_sodium_max            ,    28376,   101781, 78.20
h1_sodium_min            ,    28376,   101781, 78.20
h1_wbc_max               ,    24171,   105986, 81.43
h1_wbc_min               ,    24171,   105986, 81.43
d1_arterial_pco2_max     ,    45696,    84461, 64.89
d1_arterial_pco2_min     ,    45696,    84461, 64.89
d1_arterial_ph_max       ,    45350,    84807, 65.16
d1_arterial_ph_min       ,    45350,    84807, 65.16
d1_arterial_po2_max      ,    46147,    84010, 64.55
d1_arterial_po2_min      ,    46147,    84010, 64.55
d1_pao2fio2ratio_max     ,    36818,    93339, 71.71
d1_pao2fio2ratio_min     ,    36818,    93339, 71.71
h1_arterial_pco2_max     ,    22491,   107666, 82.72
h1_arterial_pco2_min     ,    22491,   107666, 82.72
h1_arterial_ph_max       ,    22308,   107849, 82.86
h1_arterial_ph_min       ,    22308,   107849, 82.86
h1_arterial_po2_max      ,    22712,   107445, 82.55
h1_arterial_po2_min      ,    22712,   107445, 82.55
h1_pao2fio2ratio_max     ,    16760,   113397, 87.12
h1_pao2fio2ratio_min     ,    16760,   113397, 87.12
