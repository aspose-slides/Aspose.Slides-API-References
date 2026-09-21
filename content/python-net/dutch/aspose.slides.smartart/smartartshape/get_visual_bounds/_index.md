---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Haalt de visuele begrenzing van de vorm op, berekend op basis van de gerenderde inhoud.

### Retour

Een **aspose.slides.RectangleF** die de visuele begrenzing van de vorm in slidecoördinaten vertegenwoordigt.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de asgeoriënteerde begrenzingen van alle inhoud die door de vorm wordt geproduceerd tijdens het renderen in slidecoördinaten.
             
             Deze begrenzingen kunnen afwijken van de modelbegrenzingen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud verder reikt
             dan de slide-oorsprong.
             
             De visuele begrenzingen houden rekening met rendergerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen,
             tekstindeling en overlopen, SmartArt-geometrie, en andere layout-effecten
             die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.
             
             De geretourneerde begrenzingen worden niet bijgesneden tot de slide-rechthoek.



### Zie ook
* klasse [`SmartArtShape`](/slides/python-net/nl/aspose.slides.smartart/smartartshape)
* module [`aspose.slides.smartart`](/slides/python-net/nl/aspose.slides.smartart)
* bibliotheek [`Aspose.Slides`](/slides/python-net)