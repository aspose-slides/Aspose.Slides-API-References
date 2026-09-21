---
title: add_section_zoom_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Maakt een nieuw Section Zoom frame en voegt het toe aan het einde van de vormverzameling.

### Retour

Het nieuw aangemaakte [`ISectionZoomFrame`](/slides/python-net/nl/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | De x-coördinaat van het nieuwe Section Zoom frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Section Zoom frame, in punten. |
| width | **float** | De breedte van het nieuwe Section Zoom frame, in punten. |
| height | **float** | De hoogte van het nieuwe Section Zoom frame, in punten. |
| section | [`ISection`](/slides/python-net/nl/aspose.slides/isection) | De [`ISection`](/slides/python-net/nl/aspose.slides/isection) waarnaar verwezen wordt door het Section Zoom frame; <br/><br/>            moet tot deze presentatie behoren en minstens één dia bevatten. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de verwijzende section niet tot de huidige presentatie behoort of geen dia's bevat. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Maakt een nieuw Section Zoom frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormverzameling.

### Retour

Het nieuw aangemaakte [`ISectionZoomFrame`](/slides/python-net/nl/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | De x-coördinaat van het nieuwe Section Zoom frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Section Zoom frame, in punten. |
| width | **float** | De breedte van het nieuwe Section Zoom frame, in punten. |
| height | **float** | De hoogte van het nieuwe Section Zoom frame, in punten. |
| section | [`ISection`](/slides/python-net/nl/aspose.slides/isection) | De [`ISection`](/slides/python-net/nl/aspose.slides/isection) waarnaar verwezen wordt door het Section Zoom frame; <br/><br/>            moet tot deze presentatie behoren en minstens één dia bevatten. |
| image | [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) | De [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) die wordt weergegeven binnen het Section Zoom frame. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de verwijzende section niet tot de huidige presentatie behoort of geen dia's bevat. |



### Zie ook
* klasse [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage)
* klasse [`ISection`](/slides/python-net/nl/aspose.slides/isection)
* klasse [`ISectionZoomFrame`](/slides/python-net/nl/aspose.slides/isectionzoomframe)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)