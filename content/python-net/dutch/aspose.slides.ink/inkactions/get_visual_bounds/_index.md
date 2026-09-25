---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die berekend zijn op basis van de gerenderde inhoud.

### Retourwaarde

Een [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) die de visuele grenzen van de vorm
             in dia-coördinaten weergeeft.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen
De geretourneerde rechthoek vertegenwoordigt de as-uitgelijnde grenzen van alle inhoud
             die door de vorm tijdens het renderen in dia-coördinaten wordt geproduceerd.

Deze grenzen kunnen afwijken van de modelgrenzen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud verder reikt
             buiten de oorsprong van de dia.

De visuele grenzen houden rekening met render-gerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en aansluitingen,
             tekstindeling en overflow, SmartArt-geometrie, en andere layouteffecten
             die van invloed zijn op het uiteindelijke gerenderde uiterlijk van de vorm.

De geretourneerde grenzen zijn niet bijgesneden tot de dia-rechthoek.



### Zie ook
* klasse [`InkActions`](/slides/python-net/nl/aspose.slides.ink/inkactions)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides.ink`](/slides/python-net/nl/aspose.slides.ink)
* bibliotheek [`Aspose.Slides`](/slides/python-net)