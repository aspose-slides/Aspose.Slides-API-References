---
title: get_thumbnails method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/presentation/get_thumbnails/
weight: 40
---


## get_thumbnails {#asposeslidesexportirenderingoptions}
Returns a Thumbnail Bitmap objects for all slides of a presentation.

### Returns

Bitmap objects.



```python
def get_thumbnails(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Tiff options. |


## get_thumbnails {#asposeslidesexportirenderingoptions-listint}
Returns a Thumbnail Bitmap objects for specified slides of a presentation.

### Returns

Bitmap objects.



```python
def get_thumbnails(self, options, slides):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Tiff options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |


## get_thumbnails {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size.

### Returns

Bitmap objects.



```python
def get_thumbnails(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Tiff options. |
| image_size | **aspose.pydrawing.Size** | Size of the image to create. |


## get_thumbnails {#asposeslidesexportirenderingoptions-float-float}
Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling.

### Returns

Bitmap objects.



```python
def get_thumbnails(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Tiff options. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |


## get_thumbnails {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size.

### Returns

Bitmap objects.



```python
def get_thumbnails(self, options, slides, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Tiff options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| image_size | **aspose.pydrawing.Size** | Size of the image to create. |


## get_thumbnails {#asposeslidesexportirenderingoptions-listint-float-float}
Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling.

### Returns

Bitmap objects.



```python
def get_thumbnails(self, options, slides, scale_x, scale_y):
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

