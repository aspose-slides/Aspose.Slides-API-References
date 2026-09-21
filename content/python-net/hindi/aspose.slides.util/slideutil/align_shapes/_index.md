---
title: align_shapes method
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
स्लाइड पर सभी आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें एक-दूसरे के सापेक्ष संरेखित करता है।


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/hi/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide) | Parent slide. |


## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
ग्रुप शेप के भीतर सभी आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें एक-दूसरे के सापेक्ष संरेखित करता है।


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/hi/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape) | Parent group shape. |


## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
स्लाइड पर चयनित आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें एक-दूसरे के सापेक्ष संरेखित करता है।


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/hi/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide) | Parent slide. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |


## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
ग्रुप शेप के भीतर चयनित आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें एक-दूसरे के सापेक्ष संरेखित करता है।


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/hi/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape) | Parent group shape. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |



### संबन्धित देखें
* क्लास [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide)
* क्लास [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)
* एन्यूमरेशन [`ShapesAlignmentType`](/slides/python-net/hi/aspose.slides/shapesalignmenttype)
* क्लास [`SlideUtil`](/slides/python-net/hi/aspose.slides.util/slideutil)
* मॉड्यूल [`aspose.slides.util`](/slides/python-net/hi/aspose.slides.util)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)