---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Berekent de visuele begrenzing van de vorm op basis van de gerenderde inhoud.

### Returns

Een [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) die de visuele begrenzing van de vorm weergeeft
             in dia-coördinaten.



```python
def get_visual_bounds(self):
    ...
```

### Remarks

De geretourneerde rechthoek stelt de as-uitgelijnde begrenzing van alle inhoud voor
             die door de vorm wordt geproduceerd tijdens het renderen in de dia-coördinatenruimte.

Deze begrenzingen kunnen afwijken van de modelbegrenzingen van de vorm
             ( [`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height) )
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud verder reikt dan de oorsprong van de dia.

De visuele begrenzing houdt rekening met rendergerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen,
             tekstlay-out en overflow, SmartArt-geometrie en andere lay-outeffecten
             die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.

De geretourneerde begrenzingen worden niet bijgesneden tot de dia-rechthoek.

### Zie ook
* klasse [`AutoShape`](/slides/python-net/nl/aspose.slides/autoshape)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)