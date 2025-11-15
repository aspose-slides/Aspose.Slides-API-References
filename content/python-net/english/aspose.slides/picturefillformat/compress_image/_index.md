---
title: compress_image method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/picturefillformat/compress_image/
weight: 10
---


## compress_image {#bool-asposeslidesexportpicturescompression}
Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

### Returns

A **bool** indicating whether the image was successfully compressed. Returns **True** if the image was resized or cropped, otherwise **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | [`PicturesCompression`](/slides/python-net/aspose.slides.export/picturescompression) | The target resolution for compression, specified as a value of the [`PicturesCompression`](/slides/python-net/aspose.slides.export/picturescompression) enum. |

### Remarks

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when the resolution is not a valid value. |


## compress_image {#bool-float}
Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

### Returns

A **bool** indicating whether the image was successfully compressed. Returns **True** if the image was resized or cropped, otherwise **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | **float** | The target resolution in DPI. This value must be positive and defines how the image will be resized. |

### Remarks

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when the resolution is not a positive value. |



### See Also
* class [`PictureFillFormat`](/slides/python-net/aspose.slides/picturefillformat)
* enumeration [`PicturesCompression`](/slides/python-net/aspose.slides.export/picturescompression)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

