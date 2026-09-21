---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die zijn berekend op basis van de gerenderde inhoud.

### Retour

Een **aspose.slides.RectangleF** dat de visuele grenzen van de vorm weergeeft
             in dia-coördinaten.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek stelt de as-uitgelijnde grenzen van alle inhoud
             voor die door de vorm tijdens het renderen in de dia-coördinatenruimte wordt geproduceerd.
            
             Deze grenzen kunnen afwijken van de modelgrenzen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud verder reikt dan de oorsprong van de dia.
            
             De visuele grenzen houden rekening met rendergerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen,
             tekstlayout en overflow, SmartArt-geometrie, en andere layouteffecten die van invloed zijn op het uiteindelijke gerenderde uiterlijk van de vorm.
            
             De geretourneerde grenzen zijn niet bijgesneden tot de dia-rechthoek.



### Zie ook
* klasse [`Connector`](/slides/python-net/nl/aspose.slides/connector)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)