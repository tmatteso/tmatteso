Hi, I am Tomas Matteson, a graduating master's student from the School of Computer Science at Carnegie Mellon. 
 
My interests are primarily in applying machine learning methods to solve high impact problems in Cell Systems Biology and Structural Biology. In particular, I find myself interested in deep learned methods that rise above sample inefficiency and can utilize domain knowledge to constrain their search space. 

With regard to Cell Systems Biology, I am drawn to Multimodal Machine Learning methods that incorporate DNA sequence, chromatin accessibility, multiplexed FISH imaging, and RNA sequence to learn regulatory networks through cyclic translation or multimodal fusion techniques. I am also drawn to (deep) graphical methods in this case, where a neural net may parameterize a probabilistic graphical model that exhibits known regulatory hierarchy, so we may distill changes in regulatory dynamics explainably. In particular, using deep multimodal techniques to parameterize Bayesian Networks may help in our understanding of cell lineage tracing, both in developmental differentiation and in cancer progression. If a joint representation learned from such data could be used to paramterize such a model, it would also likely serve as an excellent embedding to use in multimodal manifold learning of the cell state space.

With regard to Structural Biology, recent advances in deep neural networks for 3D point clouds have caught my interest. Tensor Field Networks, and their application to RNA structure prediction have proved quite useful. More recently, E(n) Equivariant Graph Neural Networks have added reflection equivariance to the permutation, rotation, and translation equivariance of other models, all useful properties for 3D modeling. Combining 3D scoring functions that use these methods with large transformer models like Alphafold2 can give us the best of both worlds. The transformer will attend over the sequence input and propose point cloud structures based on multiple sequence alignments (doing the heavy lifting of sequence to structure). Then, a "sufficiently" trained 3D point cloud scoring function may greatly prune the search space further with its learned understanding of molecular biophysics on the point clouds themselves. In this way we can give back to these structural models the precepts of physical knowledge, making them more performant on low coverage alignments and generally more sample efficient. 

I am currently looking for new opportunities, both in industry and in academia, as I graduate this December. If you would like to contact me or learn more, please reach out via my Linkedin: https://www.linkedin.com/in/tomas-matteson-542b16253/


<!---
tmatteso/tmatteso is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
