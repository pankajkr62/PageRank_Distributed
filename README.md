# PageRank_Distributed

## Overview
The aim of the project is to get started with Apache Spark and Hadoop File Systems.

## Implementation
For this project, we have implemented PageRank algorithm on the Wikipedia Edge Relationship Dataset.
Each line in the dataset is in the form 'A\tB', interpreted as a directed edge from A to B.
We tried to compute the pageranks of all nodes with non-zero incoming edges in the Wikipedia dataset.

The project consists of the following different set-ups of Pagerank on WikiDataset: 

1. PageRank_normal :     Normal implementation. 
2. PageRank_Partition :  Involves custom data partitioning involved across 3 nodes.
3. PageRank_Persist_Partition: Involved data partitioning and enabling in-memory store. 
4. PageRank_FaultTolerance : Involves killing one machine at different timelines (25% and 75% lifetime)

## Metrics 
We have drawn our observations from looging following metrics during execution times 
 1. Job completion times 
 2. Network traffic(recv/send data) across worker nodes. 
 3. Disk read/write (read/writ data) across worker nodes. 

## Results
We have provided all information ( Implementation, Observations, Graphs etc ) in a single report here. 
Please have a look for more info. 






