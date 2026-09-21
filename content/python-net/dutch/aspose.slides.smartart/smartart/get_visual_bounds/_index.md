---
title: get_visual_bounds method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Haalt de visuele grenzen van de vorm op die zijn berekend op basis van de gerenderde inhoud.

### Retourneert

Een **aspose.slides.RectangleF** die de visuele grenzen van de vorm weergeeft in diacoördinaten.



```python
def get_visual_bounds(self):
    ...
```


### Opmerkingen

De geretourneerde rechthoek vertegenwoordigt de as-uitgelijnde grenzen van alle inhoud die door de vorm wordt geproduceerd tijdens het renderen in de diacoördinaatruimte.

Deze grenzen kunnen afwijken van de modelgrenzen van de vorm ([`Shape.x`](/slides/python-net/nl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/nl/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/nl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/nl/aspose.slides/shape/height)) en kunnen negatieve coördinaten bevatten als de gerenderde inhoud verder reikt dan de oorsprong van de dia.

De visuele grenzen houden rekening met rendergerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijnbreedte en verbindingen, tekstlay-out en overflow, SmartArt-geometrie en andere layouteffecten die van invloed zijn op het uiteindelijke gerenderde uiterlijk van de vorm.

De geretourneerde grenzen worden niet afgeknipt tot de diarrechthoek.



### Zie ook
* klasse [`SmartArt`](/slides/python-net/nl/aspose.slides.smartart/smartart)
* module [`aspose.slides.smartart`](/slides/python-net/nl/aspose.slides.smartart)
* bibliotheek [`Aspose.Slides`](/slides/python-net)