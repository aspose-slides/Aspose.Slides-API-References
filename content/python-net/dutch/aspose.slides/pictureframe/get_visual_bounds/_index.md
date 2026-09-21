---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op, berekend op basis van de gerenderde inhoud.

### Retourneert

Een **aspose.slides.RectangleF** die de visuele grenzen van de vorm in slide-coördinaten vertegenwoordigt.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de asgeoriënteerde grenzen van alle inhoud die door de vorm wordt geproduceerd tijdens het renderen in slide-coördinatenruimte.

Deze grenzen kunnen verschillen van de modelgrenzen van de vorm ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height)) en kunnen negatieve coördinaten bevatten als de gerenderde inhoud zich buiten de oorsprong van de dia uitstrekt.

De visuele grenzen houden rekening met rendergerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijndikte en verbindingen, tekstindeling en overflow, SmartArt-geometrie en andere layout-effecten die van invloed zijn op het uiteindelijke gerenderde uiterlijk van de vorm.

De geretourneerde grenzen worden niet bijgesneden tot de dia-rechthoek.



### Zie ook
* klasse [`PictureFrame`](/slides/python-net/nl/aspose.slides/pictureframe)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)