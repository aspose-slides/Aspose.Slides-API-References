---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die zijn berekend op basis van de gerenderde content.

### Retour

Een **aspose.slides.RectangleF** die de visuele grenzen van de vorm in slide-coördinaten weergeeft.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de as-uitgelijnde grenzen van alle content die door de vorm tijdens het renderen wordt geproduceerd in slide-coördinatenruimte.

Deze grenzen kunnen afwijken van de modelgrenzen van de vorm ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height)) en kunnen negatieve coördinaten bevatten als de gerenderde content zich uitstrekt buiten de slide-origin.

De visuele grenzen houden rekening met rendergerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijnbreedte en hoeken, tekstlayout en overflow, SmartArt-geometrie, en andere layout-effecten die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.

De geretourneerde grenzen worden niet bijgesneden tot de slide-rechthoek.



### Zie ook
* class [`SummaryZoomSection`](/slides/python-net/nl/aspose.slides/summaryzoomsection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)