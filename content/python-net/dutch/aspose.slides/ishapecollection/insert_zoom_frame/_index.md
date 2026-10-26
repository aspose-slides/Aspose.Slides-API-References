---
title: insert_zoom_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Maakt een nieuw Zoom-frame en voegt het in de vormverzameling in op de opgegeven index.

### Retourneert

De nieuw aangemaakte [`IZoomFrame`](/slides/python-net/nl/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nul-gebaseerde index waarop het Zoom-frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | **float** | De breedte van het nieuwe Zoom-frame, in punten. |
| height | **float** | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | De [`ISlide`](/slides/python-net/nl/aspose.slides/islide) waarnaar het Zoom-frame verwijst. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de verwezen slide niet behoort tot de huidige presentatie. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vormverzameling in op de opgegeven index.

### Retourneert

De nieuw aangemaakte [`IZoomFrame`](/slides/python-net/nl/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nul-gebaseerde index waarop het Zoom-frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Zoom-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Zoom-frame, in punten. |
| width | **float** | De breedte van het nieuwe Zoom-frame, in punten. |
| height | **float** | De hoogte van het nieuwe Zoom-frame, in punten. |
| slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | De [`ISlide`](/slides/python-net/nl/aspose.slides/islide) waarnaar het Zoom-frame verwijst. |
| image | [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) | De afbeelding voor de verwezen slide [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage). |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de verwezen slide niet behoort tot de huidige presentatie. |



### Zie ook
* klasse [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* klasse [`ISlide`](/slides/python-net/nl/aspose.slides/islide)
* klasse [`IZoomFrame`](/slides/python-net/nl/aspose.slides/izoomframe)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)