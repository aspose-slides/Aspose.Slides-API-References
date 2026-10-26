---
title: to_jpeg method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Converteert de invoerpresentatie naar een reeks JPEG-formaat afbeeldingen.  
Als de uitvoer-bestandsnaam wordt opgegeven als "myPath/myFilename.jpeg",  
wordt het resultaat opgeslagen als een reeks "myPath/myFilename_N.jpeg" bestanden, waarbij N een diannummer is.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De invoerpresentatie. |
| output_file_name | **str** | De uitvoer-bestandsnaam. |

### Uitzonderingen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Converteert de invoerpresentatie naar een reeks JPEG-formaat afbeeldingen.  
Als de uitvoer-bestandsnaam wordt opgegeven als "myPath/myFilename.jpeg",  
wordt het resultaat opgeslagen als een reeks "myPath/myFilename_N.jpeg" bestanden, waarbij N een diannummer is.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De invoerpresentatie |
| output_file_name | **str** | De uitvoer-bestandsnaam. |
| image_size | [`Size`](/slides/python-net/nl/aspose.slides/size) | De grootte van elke gegenereerde afbeelding. |

### Uitzonderingen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Converteert de invoerpresentatie naar een reeks JPEG-formaat afbeeldingen.  
Als de uitvoer-bestandsnaam wordt opgegeven als "myPath/myFilename.jpeg",  
wordt het resultaat opgeslagen als een reeks "myPath/myFilename_N.jpeg" bestanden, waarbij N een diannummer is.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De invoerpresentatie. |
| output_file_name | **str** | De uitvoer-bestandsnaam. |
| scale | **float** | De schaalfactor die wordt toegepast op de uitvoerafbeeldingen ten opzichte van de oorspronkelijke diaformaat. |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | De renderopties. |

### Uitzonderingen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Zie ook
* klasse [`Convert`](/slides/python-net/nl/aspose.slides.lowcode/convert)
* klasse [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions)
* klasse [`Presentation`](/slides/python-net/nl/aspose.slides/presentation)
* klasse [`Size`](/slides/python-net/nl/aspose.slides/size)
* module [`aspose.slides.lowcode`](/slides/python-net/nl/aspose.slides.lowcode)
* bibliotheek [`Aspose.Slides`](/slides/python-net)