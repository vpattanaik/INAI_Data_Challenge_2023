# INAI Data Challenge 2023

The following repo contains codes and results that were submitted to the [2023 INAI Data Challenge](http://www.inai.ai/iraste_nxt/inai-data-analytics-challenge).

## Findings

### Anomalously high alerts by vehicle, area, and alert

- Number of data points for aoi == Nagpur: 372370

    - Vehicles with anomalously high cas_fcw alerts: [1185, 1277, 5266, 6290, 7180, 9184, 9241]
    - Vehicles with anomalously high cas_hmw alerts: [1185, 2155, 3155, 4449, 8104]
    - Vehicles with anomalously high cas_ldw alerts: [729, 1750, 2173, 4407, 5246, 8854, 9132, 9241, 9788]
    - Vehicles with anomalously high cas_pcw alerts: [1185, 2165, 3155, 5170, 7180, 9104, 9134, 9194]
    - Vehicles with anomalously high hard_brake alerts: [1195, 2173, 3105, 4125, 4296, 5206, 5246, 5256, 6230, 6290, 9184]

- Number of data points for aoi == Hyderabad: 1000534

    - Vehicles with anomalously high cas_fcw alerts: [3192, 3193, 4123, 8111, 8521, 9294]
    - Vehicles with anomalously high cas_hmw alerts: [7143, 8511, 8521, 8531]
    - Vehicles with anomalously high cas_ldw alerts: [4123, 6102]
    - Vehicles with anomalously high cas_pcw alerts: [1163, 3163, 6113, 6163]
    - Vehicles with anomalously high hard_brake alerts: [1173, 2173, 4123, 4857, 8113]

- Number of data points for aoi == -: 458616

    - Vehicles with anomalously high cas_fcw alerts: [4407, 6113, 6809, 8111, 9090, 9097, 9192]
	- Vehicles with anomalously high cas_hmw alerts: [6113, 7143, 7183, 7193]
	- Vehicles with anomalously high cas_ldw alerts: [7183, 8103, 8113, 9869]
	- Vehicles with anomalously high cas_pcw alerts: [9090, 9097]
	- Vehicles with anomalously high hard_brake alerts: [1103, 1173, 2173, 6809, 6839, 8113]

### Anomalously high alerts by vehicle, speed, and alert

- Number of data points for alert == cas_fcw: 32190

    Vehicles with anomalous cas_fcw alerts:

        | Vehicle | Speed_Bin | Speed_Bin_Count |
        |---------|-----------|-----------------|
        | 1185    | 30        | 583             |
        | 1277    | 30        | 324             |
        | 5266    | 30        | 326             |
        | 6290    | 30        | 358             |
        | 8140    | 30        | 307             |
        | 8521    | 60        | 118             |
        | 8521    | 75        | 90              |
        | 9184    | 30        | 436             |
        | 9194    | 30        | 325             |

- Number of data points for alert == cas_hmw: 360114

    Vehicles with anomalous cas_hmw alerts:

        | Vehicle | Speed_Bin | Speed_Bin_Count |
        |---------|-----------|-----------------|
        | 1185    | 30        | 2946            |
        | 2173    | 30        | 2986            |
        | 3155    | 30        | 2948            |
        | 4449    | 30        | 3115            |
        | 7143    | 30        | 3662            |
        | 7143    | 45        | 2252            |
        | 8511    | 30        | 2731            |
        | 8521    | 30        | 4214            |
        | 8521    | 45        | 2887            |
        | 8521    | 60        | 1752            |


- Number of data points for alert == cas_ldw: 1287163

    Vehicles with anomalous cas_ldw alerts:

        | Vehicle | Speed_Bin | Speed_Bin_Count |
        |---------|-----------|-----------------|
        | 3192    | 90        | 7682            |
        | 3809    | 60        | 13871           |
        | 4123    | 60        | 19654           |
        | 4123    | 75        | 12793           |
        | 4807    | 90        | 4339            |
        | 6102    | 60        | 15782           |
        | 7103    | 60        | 13687           |
        | 8103    | 75        | 16620           |
        | 8113    | 75        | 17840           |

- Number of data points for alert == cas_pcw: 119426

    Vehicles with anomalous cas_pcw alerts:

        | Vehicle | Speed_Bin | Speed_Bin_Count |
        |---------|-----------|-----------------|
        | 1185    | 30        | 447             |
        | 7171    | 90        | 1               |
        | 9134    | 30        | 358             |

