---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/islide/get_image/
weight: 10
---


## get_image {#}
Returns a Thumbnail Image object (20% of real size).

### Returns

Image object **aspose.pydrawing.Bitmap**



```python
def get_image(self):
    ...
```



## get_image {#asposepydrawingsize}
Returns an image object with specified size.

### Returns

Bitmap object.



```python
def get_image(self, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_size | **aspose.pydrawing.Size** | Size of the image to create. |


## get_image {#asposeslidesexportitiffoptions}
Returns a Thumbnail tiff bitmap object with specified parameters.

### Returns

Image object.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/aspose.slides.export/itiffoptions) | Tiff options. |


## get_image {#asposeslidesexportirenderingoptions}
Returns a Thumbnail Bitmap object.

### Returns

Bitmap objects.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |


## get_image {#float-float}
Returns an image object with custom scaling.

### Returns

Image object **aspose.pydrawing.Bitmap**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |


## get_image {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Returns a Thumbnail Bitmap object with specified size.

### Returns

Bitmap objects.



```python
def get_image(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |
| image_size | **aspose.pydrawing.Size** | Size of the image to create. |


## get_image {#asposeslidesexportirenderingoptions-float-float}
Returns a Thumbnail Bitmap object with custom scaling.

### Returns

Bitmap objects.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |



### See Also
* class [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions)
* class [`ISlide`](/slides/python-net/aspose.slides/islide)
* class [`ITiffOptions`](/slides/python-net/aspose.slides.export/itiffoptions)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

