---
title: to_png method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen.  
            Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.png", 
            wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.png", waarbij N een dia-nummer is.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De invoerpresentatie. |
| output_file_name | **str** | De bestandsnaam van de output. |

### Uitzonderingen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen.  
            Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.png", 
            wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.png", waarbij N een dia-nummer is.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De invoerpresentatie |
| output_file_name | **str** | De bestandsnaam van de output. |
| image_size | **aspose.slides.Size** | De grootte van elke gegenereerde afbeelding. |

### Uitzonderingen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen.  
            Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.png", 
            wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.png", waarbij N een dia-nummer is.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De invoerpresentatie. |
| output_file_name | **str** | De bestandsnaam van de output. |
| scale | **float** | De schaalfactor die wordt toegepast op de uitvoerafbeeldingen ten opzichte van de oorspronkelijke dia-afmeting. |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | De renderopties. |

### Uitzonderingen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Zie ook
* klasse [`Convert`](/slides/python-net/nl/aspose.slides.lowcode/convert)
* klasse [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions)
* klasse [`Presentation`](/slides/python-net/nl/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/nl/aspose.slides.lowcode)
* bibliotheek [`Aspose.Slides`](/slides/python-net)