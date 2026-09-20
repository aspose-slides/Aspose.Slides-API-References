---
title: to_jpeg method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Konverterar den angivna presentationen till en uppsättning JPEG-formatbilder.  
            Om utdatafilnamnet anges som "myPath/myFilename.jpeg", 
            sparas resultatet som en uppsättning "myPath/myFilename_N.jpeg"-filer, där N är ett bildnummer.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/sv/aspose.slides/presentation) | Den inmatade presentationen. |
| output_file_name | **str** | Utdatafilnamnet. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Konverterar den angivna presentationen till en uppsättning JPEG-formatbilder.  
            Om utdatafilnamnet anges som "myPath/myFilename.jpeg", 
            sparas resultatet som en uppsättning "myPath/myFilename_N.jpeg"-filer, där N är ett bildnummer.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/sv/aspose.slides/presentation) | Den inmatade presentationen |
| output_file_name | **str** | Utdatafilnamnet. |
| image_size | **aspose.slides.Size** | Storleken på varje genererad bild. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Konverterar den angivna presentationen till en uppsättning JPEG-formatbilder.  
            Om utdatafilnamnet anges som "myPath/myFilename.jpeg", 
            sparas resultatet som en uppsättning "myPath/myFilename_N.jpeg"-filer, där N är ett bildnummer.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/sv/aspose.slides/presentation) | Den inmatade presentationen. |
| output_file_name | **str** | Utdatafilnamnet. |
| scale | **float** | Skalfaktorn som tillämpas på utdatabilderna i förhållande till den ursprungliga bildens storlek. |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativen. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Se även
* klass [`Convert`](/slides/python-net/sv/aspose.slides.lowcode/convert)
* klass [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions)
* klass [`Presentation`](/slides/python-net/sv/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/sv/aspose.slides.lowcode)
* bibliotek [`Aspose.Slides`](/slides/python-net)