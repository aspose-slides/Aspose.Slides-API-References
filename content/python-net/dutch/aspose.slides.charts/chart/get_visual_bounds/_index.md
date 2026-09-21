---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die zijn berekend op basis van de gerenderde inhoud.

### Retourneert

A **aspose.slides.RectangleF** die de visuele grenzen van de vorm weergeeft
             in dia-coördinaten.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de langs de as uitgelijnde grenzen van alle inhoud
             die door de vorm tijdens het renderen in de dia-coördinatenruimte wordt geproduceerd.
            
             Deze grenzen kunnen verschillen van de modelgrenzen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud buiten de oorsprong van de dia zich uitstrekt.
            
             De visuele grenzen houden rekening met rendergerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen,
             tekstlayout en overflow, SmartArt-geometrie, en andere layouteffecten
             die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.
            
             De geretourneerde grenzen worden niet bijgesneden tot de dia-rechthoek.



### Zie ook
* klasse [`Chart`](/slides/python-net/nl/aspose.slides.charts/chart)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)