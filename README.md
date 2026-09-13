# Appearance-Based Similarity Search for 3D Gaussian Splatting (3DGS) Objects

A collection of web-based systems and experiments for exploring 3D Gaussian Splatting (3DGS) objects, with a focus on appearance-based and shape-based similarity search.

---

## [Splarix](https://compsci.world.coocan.jp/splarix/)

Splarix is a web-based system for appearance-based similarity search across a database of 3DGS objects generated from a large collection of computer-generated images. It computes feature descriptors for each object and uses them to retrieve objects with similar visual appearances.

- Attention-Based Set Aggregation for Retrieving 3D Gaussian Splatting Models Using Appearance, Motofumi T. Suzuki, 2026 The 10th International Conference on Graphics and Signal Processing, pp. 29–37, June 2026. ISBN: 979-8-3195-4596-1.
- Denoising Autoencoder-Based Augmentation and Canonicalization for 3D Gaussian Splatting Object Retrieval, Motofumi Suzuki, 2026 IEEE International Conference on Systems, Man, and Cybernetics (IEEE SMC 2026), October 2026.

---

## [Splarix Branch](https://compsci.world.coocan.jp/splarix_branch/)

Splarix Branch is an alternative version of Splarix with nine times as many 3DGS objects and a different mix of object shapes. It is used to evaluate both appearance-based and shape-based similarity search.

---

## [Splarix SG](https://compsci.world.coocan.jp/splarix_sg/)

Splarix SG is a viewer for inspecting 3DGS objects and verifying how they are generated from 3D mesh data and rendered 2D images.

---

## [3DGS Seeds](https://compsci.world.coocan.jp/3dgs_seeds/)

3DGS Seeds explores how random training seeds affect the resulting 3DGS objects and the feature descriptors used for similarity search in Splarix.

---

## [3DGS MNIST Viewer](https://compsci.world.coocan.jp/3dgs_mnist/)

This viewer supports similarity search across a dataset of 3DGS objects created by converting 2D handwritten digit images from MNIST into 3D meshes, applying textures, and then converting the textured meshes into 3DGS representations. It explores appearance-based search using textures and shape-based search across the ten digit classes (0–9).

Only a small number of objects are available because generating the dataset requires substantial processing time and disk space.

---

## [Superellipsoid 3DGS Explorer](https://compsci.world.coocan.jp/se3dgs/)

Superellipsoid 3DGS Explorer is an interactive viewer for exploring and comparing 3DGS representations of mathematically defined superellipsoids. These objects are generated from large collections of images rendered with POV-Ray.

- Automated Generation of Synthetic 3D Gaussian Splatting Datasets for Shape and Texture Descriptor Analysis, Motofumi Suzuki, The 11th International Conference on Information, Vol. 29(1), pp. 117–122, January 2026. ISSN: 1343-4500.

---

## [Superellipsoid 3DGS Table Viewer](https://compsci.world.coocan.jp/se3dgs2/)

Superellipsoid 3DGS Table Viewer displays superellipsoid 3DGS objects in a table for comparison. These objects are generated from large collections of images rendered with POV-Ray. Placing initial points on features such as flat surfaces and protrusions enables training on shapes that are otherwise difficult to reconstruct with 3DGS.

---

## [3DGS Splat Viewer](https://compsci.world.coocan.jp/3dgs_splat_viewer/)

3DGS Splat Viewer is a simple viewer for displaying 3DGS objects.

---

Last updated: September 2026
