---
title: remove_at method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Tar bort elementet på det angivna indexet i samlingen.


```python
def remove_at(self, index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet för elementet som ska tas bort. |

### Anmärkningar

1) För att undvika att PptxEditException kastas, kontrollera layoutens HasDependingSlides-egenskap först.  
2) Du kan också använda [`ILayoutSlide.remove`](/slides/python-net/sv/aspose.slides/ilayoutslide/remove) metod för att förenkla koden.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om layout används i presentationen (dess HasDependingSlides-egenskap är sann). |



### Se även
* klass [`MasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)