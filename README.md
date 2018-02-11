TINET: A Transfer Learning Framework for Invariant Networks
======================

Project Introduction
--------

The invariant network has shown to be a powerful way of characterizing complex system behaviors. 
However,due to the dynamic and complex nature of real-world information systems, learning a reliable invariant network in a new environment often requires continuous collecting and analyzing the system surveillance data for several weeks or even months. 
To avoid the prohibitive time and resource consuming network building process, we propose TINET, a knowledge transfer based model for accelerating invariant network construction. Extensive experiments on both synthetic and real-world datasets demonstrate the effectiveness and efficiency of TINET.

<img src="https://github.com/rackingroll/tinet/blob/master/Image/overview.PNG" width="900" height="360" />

Code
--------
We will release the code once the paper gets published.

Data
--------
The synthetic data is located in Data/Synthetic_Data/ directory.

The real-world data is located in Data/Real_Data directory. We preprocess the data into Invariant Network format. The model* files contain the adjacency matrix representation of the Invariant Network, and target*/source* files contain the identification of all the entities.

Resources  
-------- 
Chen Luo, Zhengzhang Chen, Lu-An Tang, Anshumali Shrivastava, Zhichun Li, Haifeng Chen, Jieping Ye
. [*TINET: Learning Invariant Networks via Knowledge Transfer*] Under Review.

Contact: Chen Luo (cl67@rice.edu)