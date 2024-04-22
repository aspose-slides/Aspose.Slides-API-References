---
title: get_images method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/presentation/get_images/
weight: 20
---


## get_images {#asposeslidesexportirenderingoptions}
Returns a Image objects for all slides of a presentation.

### Returns

Image objects.



```python
def get_images(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Tiff options. |


## get_images {#asposeslidesexportirenderingoptions-listint}
Returns a Thumbnail Image objects for specified slides of a presentation.

### Returns

Image objects.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Tiff options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |


## get_images {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Returns a Thumbnail Image objects for all slides of a presentation with specified size.

### Returns

Image objects.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Tiff options. |
| image_size | **aspose.pydrawing.Size** | Size of the image to create. |


## get_images {#asposeslidesexportirenderingoptions-float-float}
Returns a Thumbnail Image objects for all slides of a presentation with custom scaling.

### Returns

Image objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Tiff options. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |


## get_images {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Returns a Thumbnail Image objects for specified slides of a presentation with specified size.

### Returns

Image objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Tiff options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| image_size | **aspose.pydrawing.Size** | Size of the image to create. |


## get_images {#asposeslidesexportirenderingoptions-listint-float-float}
Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling.

### Returns

Image objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Tiff options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |



### See Also
* class [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions)
* class [`Presentation`](/slides/python-net/aspose.slides/presentation)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

