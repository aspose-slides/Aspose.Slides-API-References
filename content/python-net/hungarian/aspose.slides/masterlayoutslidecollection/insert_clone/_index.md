---
title: insert_clone method
second_title: Aspose.Slides Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Beszúr egy másolatot a megadott elrendezési diáról a gyűjtemény megadott pozíciójába.

### Visszatérési érték
Beszúrt dia.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az új dia indexe. |
| source_layout | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | A klónozandó dia. |

### Megjegyzés
Az új elrendezés a szülő fő diához lesz kapcsolva ezen elrendezési diák gyűjteményéhez. So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint.

### Lásd még
* class [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* class [`MasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)