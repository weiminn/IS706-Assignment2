Concern Localization using Information Retrieval

**********************
* Problem Definition *
**********************

Many software maintenance activities need to find code units (functions, files, etc.) that implement a certain concern (features, bugs, etc.). To facilitate such activities, many approaches have been proposed to automatically link code units with concerns described in natural languages, which are termed as concern localization and often employ Information Retrieval (IR) techniques. There has not been a study that evaluates and compares the effectiveness of latest IR techniques on a large dataset. This study fills this gap by investigating ten IR techniques, some of which are new and have not been used for concern localization, on a Linux kernel dataset. The Linux kernel dataset contains more than 1,500 concerns that are linked to over 85,000 C functions. We have evaluated the effectiveness of the ten techniques on recovering the links between the concerns and the implementing functions and ranked the IR techniques based on their precisions on concern localization.


**********************
* Sources *
**********************

1. Folder "documents" : features (concerns) in Linux kernel.

2. Folder "queries": method units (written in C) extracted from Linux kernel source code. 