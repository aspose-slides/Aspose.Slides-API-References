---
title: remove method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
Tar bort layouten från presentationen.

```python
def remove(self):
    ...
```

### Anmärkningar

För att undvika att PptxEditException kastas, kontrollera layoutens HasDependingSlides egenskap först.

### Undantag

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om layout redan har tagits bort från presentationen eller om layout används i presentationen (dess <br/>            HasDependingSlides egenskap är sann). |

### Se även
* class [`LayoutSlide`](/slides/python-net/sv/aspose.slides/layoutslide)
* class [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)