<!-- Generated by scripts/utils/show_diar_result.sh -->
# RESULTS
## EEND-EDA model with no prior information of the number of speakers
Note that this is a preliminary experiment, and the number of speakers in both training and test sets is limited to `2` (the system still "estimates" the number of speakers).
## Environments
- date: `Tue Sep 28 18:39:31 EDT 2021`
- python version: `3.7.11 (default, Jul 27 2021, 14:32:16)  [GCC 7.5.0]`
- espnet version: `espnet 0.10.3a2`
- pytorch version: `pytorch 1.8.1+cu102`
- Git hash: `5ffc323b3c7b6123fc48eabb768776e214bc2d68`
  - Commit date: `Tue Sep 28 18:14:14 2021 -0400`

## diar_train_diar_eda_raw_max_epoch25
- Training Config: `conf/train_diar_eda.yaml`
- Inference Config: `conf/decode_diar.yaml`
### DER
`dev_clean_2_ns2_beta2_500`

|threshold_median_collar|DER|
|---|---|
|result_th0.3_med11_collar0.0|33.51|
|result_th0.3_med1_collar0.0|33.62|
|result_th0.4_med11_collar0.0|32.75|
|result_th0.4_med1_collar0.0|32.85|
|**result_th0.5_med11_collar0.0**|**32.50**|
|result_th0.5_med1_collar0.0|32.65|
|result_th0.6_med11_collar0.0|33.05|
|result_th0.6_med1_collar0.0|33.22|
|result_th0.7_med11_collar0.0|34.83|
|result_th0.7_med1_collar0.0|35.07|

## SA-EEND model with known number of speakers
## Environments
- date: `Wed Aug 25 23:29:07 EDT 2021`
- python version: `3.7.11 (default, Jul 27 2021, 14:32:16)  [GCC 7.5.0]`
- espnet version: `espnet 0.10.2a1`
- pytorch version: `pytorch 1.9.0+cu102`
- Git hash: `19bcd34f9395e01e54a97c4db5ecbcedb429dd92`
  - Commit date: `Tue Aug 24 19:50:44 2021 -0400`

## diar_train_diar_raw_max_epoch20
- Training Config: `conf/train_diar.yaml`
- Inference Config: `conf/decode_diar.yaml`
- Pretrained Model: https://zenodo.org/record/5264020
### DER
`dev_clean_2_ns2_beta2_500`

|threshold_median_collar|DER|
|---|---|
|result_th0.3_med1_collar0.0|32.42|
|result_th0.3_med11_collar0.0|32.03|
|result_th0.4_med1_collar0.0|30.96|
|result_th0.4_med11_collar0.0|30.26|
|result_th0.5_med1_collar0.0|30.35|
|**result_th0.5_med11_collar0.0**|**29.37**|
|result_th0.6_med1_collar0.0|30.77|
|result_th0.6_med11_collar0.0|29.52|
|result_th0.7_med1_collar0.0|32.60|
|result_th0.7_med11_collar0.0|31.03|
