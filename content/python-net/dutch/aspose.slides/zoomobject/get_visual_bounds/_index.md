---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op, berekend op basis van de gerenderde inhoud.

### Retourwaarde

Een [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) die de visuele grenzen van de vorm weergeeft in dia-coördinaten.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek stelt de as-uitgelijnde grenzen van alle inhoud voor die door de vorm tijdens het renderen in de dia-coördinatenruimte wordt geproduceerd.
            
Deze grenzen kunnen verschillen van de modelgrenzen van de vorm ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height)) en kunnen negatieve coördinaten bevatten als de gerenderde inhoud voorbij de oorsprong van de dia reikt.
            
De visuele grenzen houden rekening met rendergerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijnbreedte en koppelingen, tekstlay-out en overflow, SmartArt-geometrie, en andere layouteffecten die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.
            
De geretourneerde grenzen worden niet afgeknipt tot de dia-rechthoek.



### Zie ook
* klasse [`ZoomObject`](/slides/python-net/nl/aspose.slides/zoomobject)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)