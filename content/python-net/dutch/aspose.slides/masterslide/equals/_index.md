---
title: equals method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/masterslide/equals/
weight: 30
---
## equals(self, slide) {#ibaseslide}
Bepaalt of de twee IBaseSlide instanties gelijk zijn.  
De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de dia.  
Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identifier-waarden, bijvoorbeeld SlideId, en met dynamische inhoud, bijvoorbeeld de huidige datumwaarde in een Datum-placeholder.

### Retourwaarde

**true**  als de opgegeven IBaseSlide gelijk is aan de huidige IBaseSlide;  
anders, **false** .

```python
def equals(self, slide):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide) | De IBaseSlide om te vergelijken met de huidige IBaseSlide. |

### Zie ook
* klasse [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide)
* klasse [`MasterSlide`](/slides/python-net/nl/aspose.slides/masterslide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)