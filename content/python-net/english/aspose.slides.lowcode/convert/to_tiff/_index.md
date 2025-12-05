---
title: to_tiff method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.lowcode/convert/to_tiff/
weight: 60
---


## to_tiff {#presentation-str}
Converts the input presentation to a set of TIFF format images.  
            If the output file name is given as "myPath/myFilename.tiff", 
            the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number.


```python
@staticmethod
def to_tiff(pres, output_file_name):
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


## to_tiff {#presentation-str-asposeslidesexportitiffoptions-bool}
Converts the input presentation to TIFF format with custom options.
            If the output file name is given as "myPath/myFilename.tiff" and `multipage` is `false`, 
            the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number.
            Otherwise, if `multipage` is `true`, the result will be a multi-page "myPath/myFilename.tiff" document.


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/aspose.slides/presentation) | The input presentation. |
| output_file_name | **str** | The output file name. |
| options | [`ITiffOptions`](/slides/python-net/aspose.slides.export/itiffoptions) | The TIFF saving options. |
| multipage | **bool** | Specifies whether the generated TIFF document should be a multi-page. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### See Also
* class [`Convert`](/slides/python-net/aspose.slides.lowcode/convert)
* class [`ITiffOptions`](/slides/python-net/aspose.slides.export/itiffoptions)
* class [`Presentation`](/slides/python-net/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)

