---
title: to_tiff method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Converteert de invoerpresentatie naar een set TIFF-afbeeldingen.  
Als de naam van het uitvoerbestand wordt opgegeven als "myPath/myFilename.tiff", wordt het resultaat opgeslagen als een set van "myPath/myFilename_N.tiff"-bestanden, waarbij N een slide-nummer is.


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De invoerpresentatie. |
| output_file_name | **str** | De naam van het uitvoerbestand. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Converteert de invoerpresentatie naar TIFF-formaat met aangepaste opties.  
Als de naam van het uitvoerbestand wordt opgegeven als "myPath/myFilename.tiff" en `multipage` `false` is, wordt het resultaat opgeslagen als een set van "myPath/myFilename_N.tiff"-bestanden, waarbij N een slide-nummer is.  
Anders, als `multipage` `true` is, zal het resultaat een meerpagina-"myPath/myFilename.tiff"-document zijn.


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/nl/aspose.slides/presentation) | De invoerpresentatie. |
| output_file_name | **str** | De naam van het uitvoerbestand. |
| options | [`ITiffOptions`](/slides/python-net/nl/aspose.slides.export/itiffoptions) | De TIFF-opslaanopties. |
| multipage | **bool** | Specificeert of het gegenereerde TIFF-document een meerpagina-document moet zijn. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Zie ook
* klasse [`Convert`](/slides/python-net/nl/aspose.slides.lowcode/convert)
* klasse [`ITiffOptions`](/slides/python-net/nl/aspose.slides.export/itiffoptions)
* klasse [`Presentation`](/slides/python-net/nl/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/nl/aspose.slides.lowcode)
* bibliotheek [`Aspose.Slides`](/slides/python-net)