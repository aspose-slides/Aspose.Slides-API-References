---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele begrenzing van de vorm op, berekend vanuit de gerenderde inhoud.

### Retourwaarde

A [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) die de visuele begrenzing van de vorm
             in dia-coördinaten weergeeft.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen
De geretourneerde rechthoek vertegenwoordigt de langs de assen uitgelijnde begrenzing van alle inhoud
             die door de vorm tijdens het renderen is geproduceerd in de dia-coördinatenruimte.

Deze begrenzingen kunnen afwijken van de modelbegrenzingen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud zich uitstrekt
             voorbij de oorsprong van de dia.

De visuele begrenzingen houden rekening met rendergerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen,
             tekstlay-out en overflow, SmartArt-geometrie, en andere lay-outeffecten
             die van invloed zijn op het uiteindelijke gerenderde uiterlijk van de vorm.

De geretourneerde begrenzingen worden niet bijgesneden tot de dia-rechthoek.



### Zie ook
* klasse [`Ink`](/slides/python-net/nl/aspose.slides.ink/ink)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides.ink`](/slides/python-net/nl/aspose.slides.ink)
* bibliotheek [`Aspose.Slides`](/slides/python-net)