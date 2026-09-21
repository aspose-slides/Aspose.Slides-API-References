---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op, berekend op basis van de gerenderde inhoud.

### Retour

Een **aspose.slides.RectangleF** die de visuele grenzen van de vorm
             in slide-coördinaten weergeeft.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De teruggegeven rechthoek vertegenwoordigt de as-uitgelijnde grenzen van alle inhoud
             die door de vorm tijdens het renderen in slide-coördinatenruimte wordt geproduceerd.
            
             Deze grenzen kunnen afwijken van de modelgrenzen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud zich uitstrekt
             voorbij de slide-oorsprong.
            
             De visuele grenzen houden rekening met rendergerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen,
             tekstindeling en overlopen, SmartArt-geometrie, en andere lay-outeffecten
             die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.
            
             De teruggegeven grenzen worden niet bijgesneden tot de slide-rechthoek.



### Zie ook
* klasse [`GraphicalObject`](/slides/python-net/nl/aspose.slides/graphicalobject)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)