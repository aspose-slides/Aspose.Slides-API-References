---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op, berekend uit de gerenderde inhoud.

### Retour

A [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) die de visuele grenzen van de vorm weergeeft
             in dia-coördinaten.

```python
def get_visual_bounds(self):
    ...
```

### Opmerkingen
De geretourneerde rechthoek vertegenwoordigt de asuitgelijnde grenzen van alle inhoud
             die door de vorm tijdens het renderen in de dia-coördinatenruimte wordt geproduceerd.

Deze grenzen kunnen afwijken van de modelgrenzen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kan negatieve coördinaten bevatten als de gerenderde inhoud zich uitstrekt
             buiten de dia-oorsprong.

De visuele grenzen houden rekening met rendergerelateerde aspecten, zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen,
             tekstlay-out en overflow, SmartArt-geometrie, en andere lay-out-effecten
             die van invloed zijn op het uiteindelijke gerenderde uiterlijk van de vorm.

De geretourneerde grenzen worden niet bijgesneden tot de dia-rechthoek.

### Zie ook
* klasse [`Connector`](/slides/python-net/nl/aspose.slides/connector)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)