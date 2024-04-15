---
title: replace_image method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ppimage/replace_image/
weight: 10
---


## replace_image {#bytes}
Replaces image data.
            The new image's data.When newImageData parameter is null.


```python
def replace_image(self, new_image_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| new_image_data | **bytes** |  |



## replace_image {#asposepydrawingimage}
Replaces image data. Attention: when Image is metafile - it will be rasterized due to restrictions of GDI+. Use ReplaceImage(byte[]) instead
            The new image.When newImage parameter is null.


```python
def replace_image(self, new_image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| new_image | **aspose.pydrawing.Image** |  |



## replace_image {#ippimage}
Replaces image data.
            The new IPPImage.When newImage parameter is null.


```python
def replace_image(self, new_image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| new_image | [`IPPImage`](/slides/python-net/aspose.slides/ippimage) |  |



### See Also
* class [`IPPImage`](/slides/python-net/aspose.slides/ippimage)
* class [`PPImage`](/slides/python-net/aspose.slides/ppimage)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
