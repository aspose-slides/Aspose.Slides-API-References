---
title: to_tiff method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Konverterar den angivna presentationen till en uppsättning TIFF-formatbilder.  
If the output file name is given as "myPath/myFilename.tiff", the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number.


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/sv/aspose.slides/presentation) | Den angivna presentationen. |
| output_file_name | **str** | Utskriftsfilens namn. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Konverterar den angivna presentationen till TIFF-format med anpassade alternativ.  
If the output file name is given as "myPath/myFilename.tiff" and `multipage` is `false`, the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number.  
Otherwise, if `multipage` is `true`, the result will be a multi-page "myPath/myFilename.tiff" document.


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/sv/aspose.slides/presentation) | Den angivna presentationen. |
| output_file_name | **str** | Utskriftsfilens namn. |
| options | [`ITiffOptions`](/slides/python-net/sv/aspose.slides.export/itiffoptions) | Alternativen för TIFF-sparning. |
| multipage | **bool** | Anger om det genererade TIFF-dokumentet ska vara flersidigt. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Se också
* klass [`Convert`](/slides/python-net/sv/aspose.slides.lowcode/convert)
* klass [`ITiffOptions`](/slides/python-net/sv/aspose.slides.export/itiffoptions)
* klass [`Presentation`](/slides/python-net/sv/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/sv/aspose.slides.lowcode)
* bibliotek [`Aspose.Slides`](/slides/python-net)