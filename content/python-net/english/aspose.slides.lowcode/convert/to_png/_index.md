---
title: to_png method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.lowcode/convert/to_png/
weight: 40
---


## to_png {#presentation-str}
Converts the input presentation to a set of PNG format images.  
            If the output file name is given as "myPath/myFilename.png", 
            the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/aspose.slides/presentation) | The input presentation. |
| output_file_name | **str** | The output file name. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png {#presentation-str-asposepydrawingsize}
Converts the input presentation to a set of PNG format images.  
            If the output file name is given as "myPath/myFilename.png", 
            the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/aspose.slides/presentation) | The input presentation |
| output_file_name | **str** | The output file name. |
| image_size | **aspose.pydrawing.Size** | The size of each generated image. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png {#presentation-str-float-asposeslidesexportirenderingoptions}
Converts the input presentation to a set of PNG format images.  
            If the output file name is given as "myPath/myFilename.png", 
            the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/aspose.slides/presentation) | The input presentation. |
| output_file_name | **str** | The output file name. |
| scale | **float** | The scaling factor applied to the output images relative to the original slide size. |
| options | [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions) | The rendering options. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### See Also
* class [`Convert`](/slides/python-net/aspose.slides.lowcode/convert)
* class [`IRenderingOptions`](/slides/python-net/aspose.slides.export/irenderingoptions)
* class [`Presentation`](/slides/python-net/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)

