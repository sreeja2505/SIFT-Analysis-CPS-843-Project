# SIFT-Analysis-CPS-843-Project
This paper presents a strategy for extricating particular invariant highlights from pictures
that can be utilized to perform solid coordinating between diverse sees of a protest or scene. The 
highlights are invariant to picture scale and turn, and appear to supply vigorous coordination
over a considerable run of relative twisting, alter in 3D perspective, expansion of clamor, and 
alter in brightening. The features are exceedingly unmistakable, within the sense that a single
highlight can be accurately coordinated with tall likelihood against a huge database of 
highlights from numerous pictures. This paper too portrays an approach to utilizing these
highlights for question acknowledgment. 

The recognition proceeds by matching individual features to a database of features from 
known objects using a fast nearest-neighbor algorithm, followed by a Hough transform to 
identify clusters belonging to a single object, and finally performing verification through
least-squares solution for consistent pose parameters. This approach to recognition can robustly 
identify objects among clutter and occlusion while achieving near real-time performance.

This paper has also presented methods for using the key points for object recognition.
The approach we have described uses approximate nearest neighbor lookup, a Hough transform
for identifying clusters that agree on object pose, least-squares pose determination, and final 
verification. Systematic testing is needed on the data set with full 3D viewpoints and illumination 
changes. The features described in this paper use only a monochrome intensity image which is 
derived from including illumination-invariant color descriptors.

