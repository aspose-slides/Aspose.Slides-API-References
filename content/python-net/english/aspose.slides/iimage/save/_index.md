---
title: save method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iimage/save/
weight: 10
---


## save {#str}
Saves the image to a file.


```python
def save(self, filename):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | The path to the file where the image will be saved. |


## save {#str-asposeslidesimageformat}
Saves the image to a file in the specified format.


```python
def save(self, filename, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | The path to the file where the image will be saved. |
| format | [`ImageFormat`](/slides/python-net/aspose.slides/imageformat) | The image format. |


## save {#iorawiobase-asposeslidesimageformat}
Saves the image to a stream in the specified format.


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | The stream where the image will be saved. |
| format | [`ImageFormat`](/slides/python-net/aspose.slides/imageformat) | The image format. |


## save {#str-asposeslidesimageformat-int}
Saves the image to a file in the specified format and quality.


```python
def save(self, filename, format, quality):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | The path to the file where the image will be saved. |
| format | [`ImageFormat`](/slides/python-net/aspose.slides/imageformat) | The image format. |
| quality | **int** | The quality of the saved image (0 to 100).  <br/><br/>            This parameter only affects saving in [`ImageFormat.JPEG`](/slides/python-net/aspose.slides/imageformat/JPEG); for all other formats, it is ignored. |


## save {#iorawiobase-asposeslidesimageformat-int}
Saves the image to a stream in the specified format and quality.


```python
def save(self, stream, format, quality):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | The stream where the image will be saved. |
| format | [`ImageFormat`](/slides/python-net/aspose.slides/imageformat) | The image format. |
| quality | **int** | The quality of the saved image (0 to 100).  <br/><br/>            This parameter only affects saving in [`ImageFormat.JPEG`](/slides/python-net/aspose.slides/imageformat/JPEG); for all other formats, it is ignored. |



### See Also
* class [`IImage`](/slides/python-net/aspose.slides/iimage)
* enumeration [`ImageFormat`](/slides/python-net/aspose.slides/imageformat)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

