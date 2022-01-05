# Quantifying Collaboration Quality in Face-to-Face Classroom Settings Using MMLA
We present a case study that evaluates the feasibility of quantifying collaboration quality and its multiple sub-dimensions (e.g., collaboration flow) in an authentic classroom setting. We collected multimodal data (audio and logs) from two groups collaborating face-to-face and in a collaborative writing task. The paper describes our exploration of different machine learning models and compares their performance with that of human coders, in the task of estimating collaboration quality along a continuum.  Our results show that it is feasible to quantitatively estimate collaboration quality and its sub-dimensions, even from simple features of audio and log data, using machine learning.  These findings open possibilities for in-depth automated quantification of collaboration quality, and the use of more advanced features and algorithms to get their performance closer to that of human coders.
 

## Analysis results
In this study, we investigate various group level fusion techniques, namely PCA, entropy, gini, average, towards collaboration quality modeling. We found PCA as a better candidate in terms of high test performance on machine learning models.

![image](https://user-images.githubusercontent.com/21138354/148178452-4d95c013-3741-407d-83e6-f1fff21cf7d2.png)

We also explored the feasiblity of estimating various dimensions of collaboration quality (e.g., argumentation, collaboration flow, etc.) using machine learning models. We found Support vector regressor model performed comparatively good than other investigated models.
![image](https://user-images.githubusercontent.com/21138354/148178677-bb6e9176-8803-426b-8c6a-e08af23531e5.png)


## Paper link
You can check the paper [here](https://www.researchgate.net/publication/343984939_Quantifying_Collaboration_Quality_in_Face-to-Face_Classroom_Settings_Using_MMLA).


Chejara P., Prieto L.P., Ruiz-Calleja A., Rodríguez-Triana M.J., Shankar S.K., Kasepalu R. (2020) Quantifying Collaboration Quality in Face-to-Face Classroom Settings Using MMLA. In: Nolte A., Alvarez C., Hishiyama R., Chounta IA., Rodríguez-Triana M., Inoue T. (eds) Collaboration Technologies and Social Computing. CollabTech 2020. Lecture Notes in Computer Science, vol 12324. Springer, Cham. https://doi.org/10.1007/978-3-030-58157-2_11

