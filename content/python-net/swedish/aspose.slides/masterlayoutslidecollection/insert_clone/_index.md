---
title: insert_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Infogar en kopia av en specificerad layout-bild till angiven position i samlingen.

### Returnerar

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

Ny layout kommer att länkas till föräldramaster-bilden för denna layout-bilder-samling. Så detta motsvarar kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint.

### Se även
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`MasterLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/masterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)