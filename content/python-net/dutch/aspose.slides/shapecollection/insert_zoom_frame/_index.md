---
title: insert_zoom_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Maakt een nieuw Zoomframe en voegt het toe aan de vormcollectie op de opgegeven index.

### Retourwaarde

De nieuw aangemaakte [`IZoomFrame`](/slides/python-net/nl/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nul-gebaseerde index waarop het Zoomframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Zoomframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Zoomframe, in punten. |
| width | **float** | De breedte van het nieuwe Zoomframe, in punten. |
| height | **float** | De hoogte van het nieuwe Zoomframe, in punten. |
| slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | De [`ISlide`](/slides/python-net/nl/aspose.slides/islide) waarnaar wordt verwezen door het Zoomframe. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de verwijzende dia niet tot de huidige presentatie behoort. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Maakt een nieuw Zoomframe met een vooraf gedefinieerde afbeelding en voegt het toe aan de vormcollectie op de opgegeven index.

### Retourwaarde

De nieuw aangemaakte [`IZoomFrame`](/slides/python-net/nl/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nul-gebaseerde index waarop het Zoomframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Zoomframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Zoomframe, in punten. |
| width | **float** | De breedte van het nieuwe Zoomframe, in punten. |
| height | **float** | De hoogte van het nieuwe Zoomframe, in punten. |
| slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | De [`ISlide`](/slides/python-net/nl/aspose.slides/islide) waarnaar wordt verwezen door het Zoomframe. |
| image | [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) | De afbeelding voor de verwijzende dia [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage). |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de verwijzende dia niet tot de huidige presentatie behoort. |



### Zie ook
* klasse [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage)
* klasse [`ISlide`](/slides/python-net/nl/aspose.slides/islide)
* klasse [`IZoomFrame`](/slides/python-net/nl/aspose.slides/izoomframe)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)