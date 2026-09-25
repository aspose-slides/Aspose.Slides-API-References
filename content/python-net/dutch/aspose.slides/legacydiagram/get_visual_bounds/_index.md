---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op, berekend op basis van de gerenderde inhoud.

### Retourneert

Een [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) die de visuele grenzen van de vorm in dia-coördinaten weergeeft.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de as-uitgelijnde grenzen van alle inhoud
            die door de vorm wordt geproduceerd tijdens het renderen in dia-coördinaten.

            Deze grenzen kunnen afwijken van de modelgrenzen van de vorm
            ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
            en kunnen negatieve coördinaten bevatten als de gerenderde inhoud zich buiten de oorsprong van de dia uitstrekt.

            De visuele grenzen houden rekening met render-gerelateerde aspecten, zoals
            transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen,
            tekstopmaak en overflow, SmartArt-geometrie, en andere layouteffecten
            die van invloed zijn op het uiteindelijke gerenderde uiterlijk van de vorm.

            De geretourneerde grenzen worden niet bijgesneden tot de dia-rechthoek.



### Zie ook
* klasse [`LegacyDiagram`](/slides/python-net/nl/aspose.slides/legacydiagram)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)