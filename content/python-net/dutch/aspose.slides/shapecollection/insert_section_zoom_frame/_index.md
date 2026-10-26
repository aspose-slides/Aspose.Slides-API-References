---
title: insert_section_zoom_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Maakt een nieuw Section Zoom frame en voegt het toe aan de shape collection op de opgegeven index.

### Retourwaarde

Het nieuw aangemaakte [`ISectionZoomFrame`](/slides/python-net/nl/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop het Section Zoom frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Section Zoom frame, in points. |
| y | **float** | De y-coördinaat van het nieuwe Section Zoom frame, in points. |
| width | **float** | De breedte van het nieuwe Section Zoom frame, in points. |
| height | **float** | De hoogte van het nieuwe Section Zoom frame, in points. |
| section | [`ISection`](/slides/python-net/nl/aspose.slides/isection) | De [`ISection`](/slides/python-net/nl/aspose.slides/isection) waarnaar verwezen wordt door het Section Zoom frame;<br/><br/>            moet tot deze presentatie behoren en ten minste één dia bevatten. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Worpt als de verwezen sectie niet tot de huidige presentatie behoort of geen dia's bevat. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Maakt een nieuw Section Zoom frame met een vooraf gedefinieerde afbeelding en voegt het toe aan de shape collection op de opgegeven index.

### Retourwaarde

Het nieuw aangemaakte [`ISectionZoomFrame`](/slides/python-net/nl/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop het Section Zoom frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Section Zoom frame, in points. |
| y | **float** | De y-coördinaat van het nieuwe Section Zoom frame, in points. |
| width | **float** | De breedte van het nieuwe Section Zoom frame, in points. |
| height | **float** | De hoogte van het nieuwe Section Zoom frame, in points. |
| section | [`ISection`](/slides/python-net/nl/aspose.slides/isection) | De [`ISection`](/slides/python-net/nl/aspose.slides/isection) waarnaar verwezen wordt door het Section Zoom frame;<br/><br/>            moet tot deze presentatie behoren en ten minste één dia bevatten. |
| image | [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) | De afbeelding die binnen het Section Zoom frame moet worden weergegeven. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Worpt als de verwezen sectie niet tot de huidige presentatie behoort of geen dia's bevat. |



### Zie ook
* klasse [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage)
* klasse [`ISection`](/slides/python-net/nl/aspose.slides/isection)
* klasse [`ISectionZoomFrame`](/slides/python-net/nl/aspose.slides/isectionzoomframe)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)