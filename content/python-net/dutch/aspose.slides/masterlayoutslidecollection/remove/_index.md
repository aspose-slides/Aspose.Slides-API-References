---
title: remove method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Verwijdert een lay-out uit de collectie.

```python
def remove(self, value):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | De lay-out slide die uit de collectie moet worden verwijderd. |

### Opmerkingen

1) Om het werpen van de PptxEditException te voorkomen, controleer de HasDependingSlides-eigenschap van de lay-out vooraf.  
2) U kunt ook de [`ILayoutSlide.remove`](/slides/python-net/nl/aspose.slides/ilayoutslide/remove)-methode gebruiken om de code te vereenvoudigen.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Wordt gegooid als de lay-out wordt gebruikt in de presentatie (de HasDependingSlides-eigenschap is waar). |

### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`MasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)