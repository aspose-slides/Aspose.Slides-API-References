---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele begrenzingen van de vorm op, berekend op basis van de gerenderde inhoud.

### Retour
Een **aspose.slides.RectangleF** dat de visuele begrenzingen van de vorm weergeeft in slide-coördinaten.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen
De geretourneerde rechthoek vertegenwoordigt de asgeoriënteerde begrenzingen van alle inhoud die door de vorm tijdens het renderen in slide-coördinatenruimte wordt geproduceerd.
            
Deze begrenzingen kunnen afwijken van de modelbegrenzingen van de vorm ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height)) en kunnen negatieve coördinaten bevatten als de gerenderde inhoud verder reikt dan de slide-oorsprong.
            
De visuele begrenzingen houden rekening met render-gerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijnbreedte en verbindingen, tekstlayout en overflow, SmartArt-geometrie en andere layouteffecten die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.
            
De geretourneerde begrenzingen worden niet bijgesneden tot de slide-rechthoek.



### Zie ook
* klasse [`ZoomObject`](/slides/python-net/nl/aspose.slides/zoomobject)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)