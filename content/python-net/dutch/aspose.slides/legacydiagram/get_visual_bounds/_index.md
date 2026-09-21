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

### Returns

Een **aspose.slides.RectangleF** dat de visuele grenzen van de vorm
             in dia-coördinaten weergeeft.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

De geretourneerde rechthoek vertegenwoordigt de langs de assen uitgelijnde grenzen van alle inhoud
             die door de vorm tijdens het renderen in de dia-coördinatenruimte wordt geproduceerd.
            
             Deze grenzen kunnen afwijken van de modelgrenzen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud de dia-oorsprong overschrijdt.
            
             De visuele grenzen houden rekening met render-gerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en aansluitingen,
             tekstindeling en overflow, SmartArt-geometrie, en andere lay-outeffecten
             die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.
            
             De geretourneerde grenzen worden niet bijgesneden tot de dia-rechthoek.



### See Also
* klasse [`LegacyDiagram`](/slides/python-net/nl/aspose.slides/legacydiagram)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)