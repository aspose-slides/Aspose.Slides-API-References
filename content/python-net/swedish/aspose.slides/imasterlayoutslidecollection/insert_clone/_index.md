---
title: insert_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Infogar en kopia av en angiven layoutbild på en angiven position i samlingen.

### Returnvärde

Infogad bild.



```python
def insert_clone(self, index, source_layout):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Index för den nya bilden. |
| source_layout | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Bild att klona. |

### Anmärkningar

Den nya layouten kommer att länkas till den överordnade huvudbilden för denna layoutbildssamling.  
Detta motsvarar kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint.



### Se även
* class [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* class [`IMasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/imasterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)