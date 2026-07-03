# HCP_WM
Neuromatch Academy Impact Scholars Program project using HCP WM data

The HCP dataset comprises task-based fMRI from a large sample of human subjects.
In order to use this dataset, please electronically sign the HCP data use terms at [ConnectomeDB](https://db.humanconnectome.org).
Instructions for this are on pp. 24-25 of the [HCP Reference Manual](https://www.humanconnectome.org/storage/app/media/documentation/s1200/HCP_S1200_Release_Reference_Manual.pdf).


For performing the parcellation:
Parcellation_ISP.ipynb
(In this notebook we will load the voxel data)

For Data prepertion use:
ISP_Functional Connectivity with Network Statistics_WM_DataPreparation_Lagged.ipynb

For NBS analysis use:
ISP_Functional Connectivity with Network Statistics_WM_ALLCONDS_MicropublicationFigs_NBS.ipynb

For figure visualization use:
ISP_Functional Connectivity with Network Statistics_WM_ALLCONDS_MicropublicationFigs_Visualization.ipynb


Update 2026-07-03:

- New HCP download [link](https://balsa.wustl.edu/project?project=HCP_YA)
- The dataset selection is: "Task fMRI 3T Recommended"
- We used a subset of participants named: HCP_WM_Unrelated-100-subjects
- Download requires Aspera Connect program.
- The expected folder structure after axtracting archive is:
    - "100206/MNINonLinear/Results/tfMRI_WM_LR/.."
    - "100206/MNINonLinear/Results/tfMRI_WM_RL/.."
- "100206" - is just an example participant number
- Download link for 100206, as an example, is (https://balsa.wustl.edu/subject/46vPX)
