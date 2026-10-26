---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die zijn berekend op basis van de gerenderde inhoud.

### Retour
Een [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) die de visuele grenzen van de vorm in dia coördinaten weergeeft.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen
De geretourneerde rechthoek vertegenwoordigt de as-georiënteerde grenzen van alle inhoud die door de vorm tijdens het renderen in dia coördinatenruimte wordt geproduceerd.
            
Deze grenzen kunnen afwijken van de modelgrenzen van de vorm ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height)) en kunnen negatieve coördinaten bevatten als de gerenderde inhoud verder reikt dan de oorsprong van de dia.
            
De visuele grenzen houden rekening met render-gerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijndikte en hoeken, tekstindeling en -overflow, SmartArt-geometrie en andere layout-effecten die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.
            
De geretourneerde grenzen worden niet bijgesneden tot de dia-rechthoek.



### Zie ook
* class [`SmartArtShape`](/slides/python-net/nl/aspose.slides.smartart/smartartshape)
* class [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides.smartart`](/slides/python-net/nl/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)