---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slide/get_image/
weight: 40
---


## get_image {#}
Returns a Thumbnail Image object (20% of real size).


```python
def get_image(self):
    ...
```



## get_image {#asposepydrawingsize}
Returns a Thumbnail Image object with specified size.

### Returns

Image object.



```python
def get_image(self, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_size | **aspose.pydrawing.Size** | Size of the image to create. |


## get_image {#asposeslidesexportitiffoptions}
Returns a Thumbnail tiff image object with specified parameters.

### Returns

Image object.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/aspose.slides.export/itiffoptions) | Tiff options. |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull. |


## get_image {#asposeslidesexportirenderingoptions}
Returns a Thumbnail Image object.

### Returns

Image object.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


## get_image {#float-float}
Returns a Thumbnail Image object with custom scaling.

### Returns

IImage object.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |


## get_image {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Returns a Thumbnail Image object with specified size.

### Returns

Image object.



```python
def get_image(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |
| image_size | **aspose.pydrawing.Size** | Size of the image to create. |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


## get_image {#asposeslidesexportirenderingoptions-float-float}
Returns a Thumbnail Image object with custom scaling.

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

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |



### See Also
* class [`IImage`](/slides/python-net/aspose.slides/iimage)
* class [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions)
* class [`ITiffOptions`](/slides/python-net/aspose.slides.export/itiffoptions)
* class [`Slide`](/slides/python-net/aspose.slides/slide)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

