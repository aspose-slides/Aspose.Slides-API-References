---
title: remove method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Verwijdert een lay-out uit de collectie.

```python
def remove(self, value):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | De layout-dia om te verwijderen uit de collectie. |

### Opmerkingen

1) Om het gooien van de PptxEditException te voorkomen, controleer eerst de HasDependingSlides-eigenschap van de lay-out.
2) Je kunt ook de [`ILayoutSlide.remove`](/slides/python-net/nl/aspose.slides/ilayoutslide/remove)-methode gebruiken om de code te vereenvoudigen.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Wordt gegooid als de lay-out wordt gebruikt in de presentatie (de HasDependingSlides-eigenschap is true). |

### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`LayoutSlideCollection`](/slides/python-net/nl/aspose.slides/layoutslidecollection)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)