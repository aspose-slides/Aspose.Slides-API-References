---
title: get_images method
second_title: Aspose.Slides للبايثون عبر .NET - مرجع API
description: 
type: docs
url: /ar/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Returns a Thumbnail Image objects for all slides of a presentation.

### القيم المرجعة

Bitmap objects.



```python
def get_images(self, options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | Rendering options. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Returns a Thumbnail Bitmap objects for specified slides of a presentation.

### القيم المرجعة

Bitmap objects.



```python
def get_images(self, options, slides):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Returns a Thumbnail Image objects for all slides of a presentation with specified size.

### القيم المرجعة

Bitmap objects.



```python
def get_images(self, options, image_size):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | Rendering options. |
| image_size | [`Size`](/slides/python-net/ar/aspose.slides/size) | Size of the image to create. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Returns a Thumbnail Image objects for all slides of a presentation with custom scaling.

### القيم المرجعة

Bitmap objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | Rendering options. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Returns a Thumbnail Image objects for specified slides of a presentation with specified size.

### القيم المرجعة

Bitmap objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| image_size | [`Size`](/slides/python-net/ar/aspose.slides/size) | Size of the image to create. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling.

### القيم المرجعة

Bitmap objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |



### انظر أيضًا
* الفئة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)
* الفئة [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions)
* الفئة [`Size`](/slides/python-net/ar/aspose.slides/size)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)