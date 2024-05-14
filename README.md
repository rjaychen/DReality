# DReality
Diminished Reality Papers, restructured from # 2 below.
## General Papers
1. [Towards Understanding DR](https://dl.acm.org/doi/pdf/10.1145/3491102.3517452)
- Defines DR and describes various techniques used to achieve DR, providing a user study comparing certain combinations of techniques.
2. [A survey of DR](https://link.springer.com/article/10.1186/s41074-017-0028-1)
- Outline of all kinds of DR techniques, implementations, and links to further papers.
## Effects/Techniques
### Diminish
Change the color information of the visual field, e.g. transparency, blur, reduce saliency, desaturate, reduce contrast, reduce scale.
### See-through
Occlude objects by superimposing images of their background (background known).
#### Observing Backgrounds
- Acquire background information by capturing different viewpoints or image sets in advance, and reusing them in the XR experience.
### Replace
Overlay a virtual object on real objects.
### Inpaint
Generate plausible background images based on surroundings (background unknown).

## Steps in the DR Pipeline
### Region of Interest (ROI) detection
- Finding bounding boxes, point cloud regions, or silhouettes of objects to minimize artifacts when using DR techniques.
### Hidden view generation
- Recovering of background in ROIs by either background observation (mentioned before), or inpainting.
### Composition
- Postprocessing methods that smooth real-virtual boundaries.

## Use Cases
- Clutter Management
- Search
- Privacy Protection
- Remote Guidance
- Translation
