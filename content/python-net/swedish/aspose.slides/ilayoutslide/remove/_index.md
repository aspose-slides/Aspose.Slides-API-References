---
title: remove method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
Tar bort layout från presentationen.


```python
def remove(self):
    ...
```


### Anmärkningar

För att undvika att PptxEditException kastas, kontrollera layoutens HasDependingSlides-egenskap först.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om layout redan har tagits bort från presentationen eller om layout används i presentationen (dess <br/>            HasDependingSlides-egenskap är sann). |



### Se också
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)