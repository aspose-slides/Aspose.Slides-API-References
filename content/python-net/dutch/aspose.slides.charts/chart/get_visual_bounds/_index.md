---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die zijn berekend uit de gerenderde inhoud.

### Retourneert

Een [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) die de visuele grenzen van de vorm weergeeft
             in dia-coördinaten.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek stelt de as-uitgelijnde grenzen van alle inhoud voor
             die door de vorm wordt geproduceerd tijdens het renderen in de dia-coördinatenruimte.

Deze grenzen kunnen verschillen van de modelgrenzen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud zich uitstrekt
             buiten de oorsprong van de dia.

De visuele grenzen houden rekening met rendergerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en -verbindingen,
             tekstindeling en overlopen, SmartArt-geometrie, en andere layouteffecten
             die invloed hebben op het uiteindelijke gerenderde uiterlijk van de vorm.

De geretourneerde grenzen worden niet bijgesneden tot de dia-rechthoek.



### Zie ook
* klasse [`Chart`](/slides/python-net/nl/aspose.slides.charts/chart)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)