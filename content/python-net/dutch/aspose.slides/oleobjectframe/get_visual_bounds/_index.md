---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele begrenzing van de vorm op, berekend op basis van de gerenderde inhoud.

### Retour

Een [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) dat de visuele begrenzing van de vorm
             in dia-coördinaten weergeeft.

```python
def get_visual_bounds(self):
    ...
```

### Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de as-uitgelijnde begrenzing van alle inhoud
             die door de vorm wordt geproduceerd tijdens het renderen in dia-coördinatenruimte.
            
             Deze begrenzingen kunnen afwijken van de modelbegrenzingen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud verder strekt
             voorbij de oorsprong van de dia.
            
             De visuele begrenzingen houden rekening met rendergerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen,
             tekstlay-out en overflow, SmartArt-geometrie, en andere lay-out effecten
             die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.
            
             De geretourneerde begrenzingen worden niet bijgesneden tot de dia-rechthoek.

### Zie ook
* klasse [`OleObjectFrame`](/slides/python-net/nl/aspose.slides/oleobjectframe)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)