---
title: add_zoom_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormverzameling.

### Retourneert

Het nieuw aangemaakte [`IZoomFrame`](/slides/python-net/nl/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | **float** | De breedte van het nieuwe Zoom-frame, in punten. |
| height | **float** | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | De [`ISlide`](/slides/python-net/nl/aspose.slides/islide) waarnaar verwezen wordt door het Zoom-frame;<br/><br/>            moet tot deze presentatie behoren. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de verwezen slide niet tot de huidige presentatie behoort. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormverzameling.

### Retourneert

Het nieuw aangemaakte [`IZoomFrame`](/slides/python-net/nl/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | **float** | De breedte van het nieuwe Zoom-frame, in punten. |
| height | **float** | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | De [`ISlide`](/slides/python-net/nl/aspose.slides/islide) waarnaar verwezen wordt door het Zoom-frame;<br/><br/>            moet tot deze presentatie behoren. |
| image | [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) | De afbeelding voor de verwezen slide [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage). |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de verwezen slide niet tot de huidige presentatie behoort. |



### Zie ook
* klasse [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage)
* klasse [`ISlide`](/slides/python-net/nl/aspose.slides/islide)
* klasse [`IZoomFrame`](/slides/python-net/nl/aspose.slides/izoomframe)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)