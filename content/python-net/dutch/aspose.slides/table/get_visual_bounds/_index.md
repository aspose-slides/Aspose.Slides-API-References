---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die zijn berekend op basis van de weergegeven inhoud.

### Retour

Een [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) die de visuele grenzen van de vorm vertegenwoordigt
in slide-coördinaten.

```python
def get_visual_bounds(self):
    ...
```

### Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de as-uitgelijnde grenzen van alle inhoud die door de vorm wordt geproduceerd tijdens het renderen in slide-coördinatenruimte.

Deze grenzen kunnen afwijken van de modelgrenzen van de vorm ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height)) en kunnen negatieve coördinaten bevatten als de weergegeven inhoud zich buiten de slide-oorsprong uitstrekt.

De visuele grenzen houden rekening met rendergerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijndikte en hoeken, tekstlay-out en overflow, SmartArt-geometrie, en andere lay-outeffecten die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.

De geretourneerde grenzen worden niet bijgesneden tot de slide-rechthoek.

### Zie ook
* klasse [`Table`](/slides/python-net/nl/aspose.slides/table)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)