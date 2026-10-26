---
title: to_png method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Konverterar den angivna presentationen till en uppsättning PNG-formatbilder.  
            Om utdatafilnamnet anges som "myPath/myFilename.png", 
            sparas resultatet som en uppsättning "myPath/myFilename_N.png"-filer, där N är ett bildnummer.


```python
@staticmethod
def to_png(pres, output_file_name):
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


## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Konverterar den angivna presentationen till en uppsättning PNG-formatbilder.  
            Om utdatafilnamnet anges som "myPath/myFilename.png", 
            sparas resultatet som en uppsättning "myPath/myFilename_N.png"-filer, där N är ett bildnummer.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/sv/aspose.slides/presentation) | Den inmatade presentationen |
| output_file_name | **str** | Utdatafilnamnet. |
| image_size | [`Size`](/slides/python-net/sv/aspose.slides/size) | Storleken på varje genererad bild. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Konverterar den angivna presentationen till en uppsättning PNG-formatbilder.  
            Om utdatafilnamnet anges som "myPath/myFilename.png", 
            sparas resultatet som en uppsättning "myPath/myFilename_N.png"-filer, där N är ett bildnummer.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/sv/aspose.slides/presentation) | Den inmatade presentationen. |
| output_file_name | **str** | Utdatafilnamnet. |
| scale | **float** | Skalfaktorn som tillämpas på utdata-bilderna i förhållande till originalbildens storlek. |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativen. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Se även
* klass [`Convert`](/slides/python-net/sv/aspose.slides.lowcode/convert)
* klass [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions)
* klass [`Presentation`](/slides/python-net/sv/aspose.slides/presentation)
* klass [`Size`](/slides/python-net/sv/aspose.slides/size)
* modul [`aspose.slides.lowcode`](/slides/python-net/sv/aspose.slides.lowcode)
* bibliotek [`Aspose.Slides`](/slides/python-net)