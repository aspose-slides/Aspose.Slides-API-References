---
title: remove method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
Verwijdert een lay-out uit de verzameling.

```python
def remove(self, value):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | The layout slide to remove from the collection. |

### Opmerkingen

1) Om het gooien van de PptxEditException te voorkomen, controleer de HasDependingSlides-eigenschap van de layout eerst.  
2) Je kunt ook de methode [`ILayoutSlide.remove`](/slides/python-net/nl/aspose.slides/ilayoutslide/remove) gebruiken om de code te vereenvoudigen.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Wordt gegooid als de lay-out wordt gebruikt in de presentatie (de HasDependingSlides-eigenschap is true). |

### Zie ook
* klasse [`GlobalLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/globallayoutslidecollection)
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)