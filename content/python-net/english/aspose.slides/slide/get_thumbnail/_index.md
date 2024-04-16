---
title: get_thumbnail method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slide/get_thumbnail/
weight: 60
---


## get_thumbnail {#}
Returns a Thumbnail Image object (20% of real size).


```python
def get_thumbnail(self):
    ...
```



## get_thumbnail {#asposeslidesexportirenderingoptions}
Returns a Thumbnail Bitmap object.

### Returns

Bitmap objects.



```python
def get_thumbnail(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | Rendering options. |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


## get_thumbnail {#asposepydrawingsize}
Returns a Thumbnail Bitmap object with specified size.

### Returns

Bitmap object.



```python
def get_thumbnail(self, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_size | **aspose.pydrawing.Size** | Size of the image to create. |


## get_thumbnail {#asposeslidesexportitiffoptions}
Returns a Thumbnail tiff bitmap object with specified parameters.

### Returns

Bitmap object.



```python
def get_thumbnail(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/aspose.slides.export/itiffoptions) | Tiff options. |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull. |


## get_thumbnail {#float-float}
Returns a Thumbnail Bitmap object with custom scaling.

### Returns

Bitmap object.



```python
def get_thumbnail(self, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |


## get_thumbnail {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Returns a Thumbnail Bitmap object with specified size.

### Returns

Bitmap objects.



```python
def get_thumbnail(self, options, image_size):
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


## get_thumbnail {#asposeslidesexportirenderingoptions-float-float}
Returns a Thumbnail Bitmap object with custom scaling.

### Returns

Bitmap objects.



```python
def get_thumbnail(self, options, scale_x, scale_y):
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
* class [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions)
* class [`ITiffOptions`](/slides/python-net/aspose.slides.export/itiffoptions)
* class [`Slide`](/slides/python-net/aspose.slides/slide)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

