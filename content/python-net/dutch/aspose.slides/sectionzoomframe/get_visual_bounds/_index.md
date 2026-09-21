---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die zijn berekend uit de gerenderde inhoud.

### Retour

Een **aspose.slides.RectangleF** die de visuele grenzen van de vorm weergeeft
             in slide-coördinaten.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek stelt de as-uitgelijnde grenzen van alle inhoud
             voor die door de vorm wordt geproduceerd tijdens het renderen in de slide-coördinaatruimte.
            
             Deze grenzen kunnen afwijken van de modelgrenzen van de vorm
             ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height))
             en kunnen negatieve coördinaten bevatten als de gerenderde inhoud zich uitstrekt
             voorbij de slide-origin.
            
             De visuele grenzen houden rekening met rendergerelateerde aspecten zoals
             transformaties (bijvoorbeeld rotatie), lijndikte en verbindingspunten,
             tekstlay-out en overflow, SmartArt-geometrie, en andere lay-outeffecten
             die de uiteindelijke gerenderde weergave van de vorm beïnvloeden.
            
             De geretourneerde grenzen worden niet bijgesneden tot de slide-rechthoek.



### Zie ook
* klasse [`SectionZoomFrame`](/slides/python-net/nl/aspose.slides/sectionzoomframe)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)