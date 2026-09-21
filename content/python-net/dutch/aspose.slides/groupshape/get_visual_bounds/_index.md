---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die zijn berekend op basis van de gerenderde inhoud.

### Retour

Een **aspose.slides.RectangleF** die de visuele grenzen van de vorm weergeeft in dia-coördinaten.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek stelt de as-uitgelijnde grenzen van alle inhoud die door de vorm wordt geproduceerd tijdens het renderen in de dia-coördinatenruimte voor.
             
             Deze grenzen kunnen verschillen van de modelgrenzen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud verder reikt
             dan de oorsprong van de dia.
             
             De visuele grenzen houden rekening met rendergerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en hoeken,
             tekstlay-out en overflow, SmartArt-geometrie, en andere layouteffecten
             die van invloed zijn op het uiteindelijke gerenderde uiterlijk van de vorm.
             
             De geretourneerde grenzen worden niet bijgesneden tot de dia-rechthoek.



### Zie ook
* klasse [`GroupShape`](/slides/python-net/nl/aspose.slides/groupshape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)