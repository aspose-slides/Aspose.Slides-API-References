---
title: to_tiff method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Converts the input presentation to a set of TIFF format images.  
            If the output file name is given as "myPath/myFilename.tiff", 
            the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number.


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hu/aspose.slides/presentation) | The input presentation. |
| output_file_name | **str** | The output file name. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Converts the input presentation to TIFF format with custom options.
            If the output file name is given as "myPath/myFilename.tiff" and `multipage` is `false`, 
            the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number.
            Otherwise, if `multipage` is `true`, the result will be a multi-page "myPath/myFilename.tiff" document.


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hu/aspose.slides/presentation) | The input presentation. |
| output_file_name | **str** | The output file name. |
| options | [`ITiffOptions`](/slides/python-net/hu/aspose.slides.export/itiffoptions) | The TIFF saving options. |
| multipage | **bool** | Specifies whether the generated TIFF document should be a multi-page. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Lásd még
* osztály [`Convert`](/slides/python-net/hu/aspose.slides.lowcode/convert)
* osztály [`ITiffOptions`](/slides/python-net/hu/aspose.slides.export/itiffoptions)
* osztály [`Presentation`](/slides/python-net/hu/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/hu/aspose.slides.lowcode)
* könyvtár [`Aspose.Slides`](/slides/python-net)