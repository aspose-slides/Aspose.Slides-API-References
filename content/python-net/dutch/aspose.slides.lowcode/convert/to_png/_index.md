---
title: to_png method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Converteert de invoerpresentatie naar een reeks afbeeldingen in PNG-formaat.  
            Als de outputbestandsnaam is opgegeven als "myPath/myFilename.png", 
            wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.png", waarbij N een slide-nummer is.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De invoerpresentatie. |
| output_file_name | **str** | De outputbestandsnaam. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Converteert de invoerpresentatie naar een reeks afbeeldingen in PNG-formaat.  
            Als de outputbestandsnaam is opgegeven als "myPath/myFilename.png", 
            wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.png", waarbij N een slide-nummer is.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De invoerpresentatie |
| output_file_name | **str** | De outputbestandsnaam. |
| image_size | [`Size`](/slides/python-net/nl/aspose.slides/size) | De grootte van elke gegenereerde afbeelding. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Converteert de invoerpresentatie naar een reeks afbeeldingen in PNG-formaat.  
            Als de outputbestandsnaam is opgegeven als "myPath/myFilename.png", 
            wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.png", waarbij N een slide-nummer is.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De invoerpresentatie. |
| output_file_name | **str** | De outputbestandsnaam. |
| scale | **float** | De schaalfactor die wordt toegepast op de uitvoerafbeeldingen ten opzichte van de oorspronkelijke slide-grootte. |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | De renderopties. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Zie Ook
* klasse [`Convert`](/slides/python-net/nl/aspose.slides.lowcode/convert)
* klasse [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions)
* klasse [`Presentation`](/slides/python-net/nl/aspose.slides/presentation)
* klasse [`Size`](/slides/python-net/nl/aspose.slides/size)
* module [`aspose.slides.lowcode`](/slides/python-net/nl/aspose.slides.lowcode)
* bibliotheek [`Aspose.Slides`](/slides/python-net)