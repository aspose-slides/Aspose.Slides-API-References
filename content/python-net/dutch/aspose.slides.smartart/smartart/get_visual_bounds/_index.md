---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op, berekend uit de gerenderde inhoud.

### Retour

Een [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) die de visuele grenzen van de vorm in slide-coördinaten weergeeft.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de langs de assen uitgelijnde grenzen van alle inhoud die door de vorm tijdens het renderen in slide-coördinatenruimte wordt geproduceerd.  

Deze grenzen kunnen afwijken van de modelgrenzen van de vorm ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height)) en kunnen negatieve coördinaten bevatten als de gerenderde inhoud zich buiten de slide-oorsprong uitbreidt.  

De visuele grenzen houden rekening met render-gerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen, tekstlayout en overflow, SmartArt-geometrie, en andere layout-effecten die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.  

De geretourneerde grenzen worden niet bijgesneden tot de slide-rechthoek.



### Zie ook
* klasse [`SmartArt`](/slides/python-net/nl/aspose.slides.smartart/smartart)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides.smartart`](/slides/python-net/nl/aspose.slides.smartart)
* bibliotheek [`Aspose.Slides`](/slides/python-net)