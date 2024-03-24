# Image-Stitching

Image stitching or photo stitching is the process of combining multiple photographic images with overlapping fields of view to produce a segmented panorama or high-resolution image. 

In this project, I would take multiple images of a similar place and then stitch all those photos to create one large panoramic image. 

For feature detection and matching, I would use some feature detection algorithms such as SIFT to identify the key points in each image. Once I get these points, I will apply matching techniques to establish correspondence between key points in different images.

I will then use the established correspondences to estimate the geometric transformations which will be needed to align the images. Then, based on the estimated transformations, we will warp and align all the images.

Finally, we would blend the images which would smoothly merge the overlapping regions of the aligned image. 

I don’t know how easy or difficult this project would be. However, the Professor can suggest if this project is doable or not.
