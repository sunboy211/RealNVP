Reference: Dinh L, Sohl-Dickstein J, Bengio S. Density estimation using real nvp[J]. arXiv preprint arXiv:1605.08803, 2016.

The domain of representation learning has undergone tremendous advances due to improved supervised learning techniques. However, unsupervised learning has the potential to leverage large pools of unlabeled data, and extend these advances to modalities that are otherwise impractical or impossible.
One principled approach to unsupervised learning is generative probabilistic modeling. Not only do generative probabilistic models have the ability to create novel content, they also have a wide range of reconstruction related applications including inpainting, denoising, colorization, and super-resolution.
As data of interest are generally high-dimensional and highly structured, the challenge in this domain is building models that are powerful enough to capture its complexity yet still trainable. We address this challenge by introducing real-valued non-volume preserving (real NVP) transformations, a tractable yet expressive approach to modeling high-dimensional data.
This model can perform efficient and exact inference, sampling and log-density estimation of data points. Moreover, the architecture presented in this paper enables exact and efficient reconstruction of input images from the hierarchical features extracted by this model.