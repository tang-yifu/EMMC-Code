# CPS Attack Detection under Limited Local Information in Cyber Security: An Ensemble Multi-node Multi-class Classification Approach: Source Code

Welcome to this repository. The Latest Updated Version code of [this paper](https://dl.acm.org/doi/abs/10.1145/3585520) is shown here, with experiments conducted by Python. 

## Abstract 
Cybersecurity breaches are common anomalies for distributed cyber-physical systems (CPS). However, the cyber security breach classification is still a difficult problem, even using cutting-edge artificial intelligence (AI) approaches. In this paper, we study a multi-class classification problem in cyber security for attack detection. A challenging multi-node data-censoring case is considered. In such a case, data within each data center/node cannot be shared while the local data is incomplete. Particularly, local nodes contain only a part of the multiple classes. In order to train a global multi-class classifier without sharing the raw data across all nodes, we design a multi-node multi-class classification ensemble approach which is the main result of our study. By gathering the estimated parameters of the binary classifiers and data densities from each local node, the missing information for each local node is completed to build the global multi-class classifier. Numerical experiments are given to validate the effectiveness of the proposed approach under the multi-node data-censoring case. Under such a case, we even show the out-performance of the proposed approach over the full-data approach.

## Files
We keep maintaining the codes and updating the newest versions, including error corrections, functional additions, etc. 

The following file helps you realize the results in the paper.

### Section 3

'compare_with_cent.ipynb': The code in order to compare the performance in Section 3.3 under both imbalanced and balanced cases of the EdgeIIoT Dataset. (Figure 5) Updated on 10th, Aug, 2023.

'EdgeIIoT_select_redistribution': The code in order to compare the performance in Section 3.3 under a balanced setting and repeat the experiment of the EdgeIIoT Dataset. (Table 6) Updated on 10th, Aug, 2023.

### Section 4

The MQTT Dataset:

'Algorithm.ipynb': The code to compare the performance in Section 4 without PCA. (Table 7 in the paper)

'Algorithm_pca.ipynb': The code to compare the performance in Section 4 after PCA. (Table 8 in the paper)

## Contact 
Please contact the authors of [this paper](https://dl.acm.org/doi/abs/10.1145/3585520) if you have any questions or comments.

