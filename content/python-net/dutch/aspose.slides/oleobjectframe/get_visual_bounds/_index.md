---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die zijn berekend op basis van de gerenderde inhoud.

### Retourneert

Een **aspose.slides.RectangleF** die de visuele grenzen van de vorm weergeeft
             in dia-coördinaten.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de as-gealigneerde grenzen van alle inhoud
             die door de vorm wordt geproduceerd tijdens het renderen in de dia-coördinatenruimte.
            
             Deze grenzen kunnen afwijken van de modelgrenzen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud zich uitstrekt
             voorbij de oorsprong van de dia.
            
             De visuele grenzen houden rekening met render-gerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en aansluitingen,
             tekstlay-out en overflow, SmartArt-geometrie, en andere lay-outeffecten
             die van invloed zijn op het uiteindelijke gerenderde uiterlijk van de vorm.
            
             De geretourneerde grenzen worden niet bijgesneden tot de dia-rechthoek.



### Zie ook
* klasse [`OleObjectFrame`](/slides/python-net/nl/aspose.slides/oleobjectframe)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)