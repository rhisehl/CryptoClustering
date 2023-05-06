# CryptoClustering

Cryptocurrency returns were evaluated to determine what clusters of currencies may make solid investments. 

By using a standard elbow curve and a PCA elbow curve, it was observed that the ideal K valeu is 4 in both instances.

![image](https://user-images.githubusercontent.com/116215793/236632518-b4cf265b-caed-4a0e-b1de-bb36b61e0653.png)

The PCA curve shows an overalll reduction in inertia, with a significant reduction right at K=4. This shows that by reducing the dimensions down to 3, the variance of the dataset as a whole was reduced. 

When evaluating the clustering results from the k=4 clustering through standard and PCA analysis, it is noted that the four clusters overlap perfectly.

![image](https://user-images.githubusercontent.com/116215793/236632717-f0db38f6-0cc2-48e3-93df-ca795ec6ab3d.png)

This is strong proof that the PCA analysis was worthwhile, as it reduced dimensionality, reduced inertia, but did not change the overall clustering pattern of the graph.
