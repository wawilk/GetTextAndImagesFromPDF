# Azure Document Intelligence / Vision AI Demo Notebooks

## There are 3 notebooks in this repo

### The first notebook, DocIntelDemo.ipynb, demonstrates OCR'ing a PDF using Document Intelligence

* Getting Paragraphs  
* Getting Tables  

### The second notebook, GetImages.ipynb, demonstrates saving embedded diagrams from a PDF page which was converted to an image

This notebook uses OpenCV to locate the diagrams from the contours on the page

* Getting a diagram.
* Getting a diagram's title.
* Constrcuting a bounding box to get both diagram and title.
* Saving the bounding box to disk as an image.

### The third notebook, visionocr.ipynb, demonstrates using the Vision AI service rather than the Document Intelligence service

to do the OCR. We will again save the embedded diagrams from the page which was converted to an image.
This notebook does not uses OpenCV but relies on the Dense Captions to locate the diagrams
