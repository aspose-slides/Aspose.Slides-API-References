---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele begrenzing van de vorm op, berekend aan de hand van de gerenderde inhoud.

### Retourneert

Een **aspose.slides.RectangleF** die de visuele begrenzing van de vorm in dia-coördinaten vertegenwoordigt.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

 De geretourneerde rechthoek vertegenwoordigt de as-gekaderde begrenzing van alle inhoud die door de vorm wordt geproduceerd tijdens het renderen in de coördinatenruimte van de dia.
 
 Deze begrenzingen kunnen afwijken van de modelbegrenzingen van de vorm ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height)) en kunnen negatieve coördinaten bevatten als de gerenderde inhoud zich uitstrekt buiten de oorsprong van de dia.
 
 De visuele begrenzingen houden rekening met rendergerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen, tekstlay-out en overflow, SmartArt-geometrie, en andere layouteffecten die van invloed zijn op het uiteindelijke gerenderde uiterlijk van de vorm.
 
 De geretourneerde begrenzingen worden niet bijgesneden tot de diarechthoek.



### Zie ook
* klasse [`Table`](/slides/python-net/nl/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)