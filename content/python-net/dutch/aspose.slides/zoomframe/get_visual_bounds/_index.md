---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele begrenzing van de vorm op, berekend op basis van de gerenderde inhoud.

### Retour

Een [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) die de visuele begrenzing van de vorm weergeeft
             in dia-coördinaten.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de as-gealigneerde begrenzing van alle inhoud
             die door de vorm wordt geproduceerd tijdens het renderen in de dia-coördinaatruimte.
            
             Deze begrenzingen kunnen afwijken van de modelbegrenzingen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud zich uitstrekt
             voorbij de oorsprong van de dia.
            
             De visuele begrenzingen houden rekening met rendergerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen,
             tekstlay-out en overflow, SmartArt-geometrie, en andere layouteffecten
             die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.
            
             De geretourneerde begrenzingen worden niet bijgesneden tot de dia-rechthoek.



### Zie ook
* klasse [`ZoomFrame`](/slides/python-net/nl/aspose.slides/zoomframe)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)