---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die zijn berekend op basis van de gerenderde inhoud.

### Retourwaarde

Een **aspose.slides.RectangleF** die de visuele grenzen van de vorm in slide-coördinaten weergeeft.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen
De geretourneerde rechthoek vertegenwoordigt de as-georiënteerde grenzen van alle inhoud
             die door de vorm wordt geproduceerd tijdens het renderen in slide-coördinatenruimte.

             Deze grenzen kunnen afwijken van de modelgrenzen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud zich uitstrekt
             voorbij de slide-oorsprong.

             De visuele grenzen houden rekening met render-gerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen,
             tekstindeling en overflow, SmartArt-geometrie, en andere layouteffecten
             die het uiteindelijke gerenderde uiterlijk van de vorm beïnvloeden.

             De geretourneerde grenzen worden niet bijgesneden tot de slide-rechthoek.



### Zie ook
* klasse [`SummaryZoomFrame`](/slides/python-net/nl/aspose.slides/summaryzoomframe)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)