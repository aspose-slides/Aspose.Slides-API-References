---
title: remove_at method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masterslidecollection/remove_at/
weight: 40
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

För att undvika att PptxEditException kastas, kontrollera masterens HasDependingSlides-egenskap i förväg.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om den master som ska tas bort används i presentationen (dess HasDependingSlides-egenskap är sann). |



### Se även
* klass [`MasterSlideCollection`](/slides/python-net/sv/aspose.slides/masterslidecollection)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)