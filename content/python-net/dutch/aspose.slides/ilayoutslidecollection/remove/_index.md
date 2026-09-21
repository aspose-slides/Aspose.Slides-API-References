---
title: remove method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/ilayoutslidecollection/remove/
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
| value | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | De lay-outdia die uit de collectie moet worden verwijderd. |

### Opmerkingen

1) Om het werpen van de PptxEditException te voorkomen, controleer vóór de HasDependingSlides-eigenschap van de lay-out.  
2) Je kunt ook de [`ILayoutSlide.remove`](/slides/python-net/nl/aspose.slides/ilayoutslide/remove)-methode gebruiken om de code te vereenvoudigen.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Werpt als de lay-out wordt gebruikt in de presentatie (de HasDependingSlides-eigenschap is true). |



### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`ILayoutSlideCollection`](/slides/python-net/nl/aspose.slides/ilayoutslidecollection)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)