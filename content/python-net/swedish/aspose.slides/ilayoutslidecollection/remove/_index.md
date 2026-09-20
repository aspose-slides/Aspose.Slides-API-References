---
title: remove method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Tar bort en layout från samlingen.


```python
def remove(self, value):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Layoutbilden som ska tas bort från samlingen. |

### Anmärkningar

1) För att undvika att PptxEditException kastas, kontrollera layout's HasDependingSlides-egenskap först.
2) Du kan också använda [`ILayoutSlide.remove`](/slides/python-net/sv/aspose.slides/ilayoutslide/remove)-metoden för att förenkla koden.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om layouten används i presentationen (dess HasDependingSlides-egenskap är sann). |



### Se även
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`ILayoutSlideCollection`](/slides/python-net/sv/aspose.slides/ilayoutslidecollection)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)