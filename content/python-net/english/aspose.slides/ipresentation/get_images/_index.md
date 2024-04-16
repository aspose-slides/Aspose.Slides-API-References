---
title: get_images method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ipresentation/get_images/
weight: 10
---


## get_images {#asposeslidesexportirenderingoptions}
Returns a Thumbnail Image objects for all slides of a presentation.

### Returns

Bitmap objects.



```python
def get_images(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |


## get_images {#asposeslidesexportirenderingoptions-listint}
Returns a Thumbnail Bitmap objects for specified slides of a presentation.

### Returns

Bitmap objects.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |


## get_images {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Returns a Thumbnail Image objects for all slides of a presentation with specified size.

### Returns

Bitmap objects.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |
| image_size | **aspose.pydrawing.Size** | Size of the image to create. |


## get_images {#asposeslidesexportirenderingoptions-float-float}
Returns a Thumbnail Image objects for all slides of a presentation with custom scaling.

### Returns

Bitmap objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |


## get_images {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Returns a Thumbnail Image objects for specified slides of a presentation with specified size.

### Returns

Bitmap objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| image_size | **aspose.pydrawing.Size** | Size of the image to create. |


## get_images {#asposeslidesexportirenderingoptions-listint-float-float}
Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling.

### Returns

Bitmap objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |



### See Also
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* class [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

