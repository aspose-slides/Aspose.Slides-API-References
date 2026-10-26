---
title: remove method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Tar bort en layout från samlingen.


```python
def remove(self, value):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Layout-bilden att ta bort från samlingen. |

### Anmärkningar

1) För att undvika att PptxEditException kastas, kontrollera layoutens HasDependingSlides-egenskap först.
2) Du kan även använda [`ILayoutSlide.remove`](/slides/python-net/sv/aspose.slides/ilayoutslide/remove)-metoden för att förenkla koden.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om layouten används i presentationen (dess HasDependingSlides-egenskap är sann). |



### Se även
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`MasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)