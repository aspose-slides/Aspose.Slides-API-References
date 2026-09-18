---
title: remove_at method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Eltávolítja a gyűjtemény megadott indexén lévő elemet.

```python
def remove_at(self, index):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az eltávolítandó elem nulla-alapú indexe. |

### Megjegyzések

A PptxEditException dobásának elkerülése érdekében ellenőrizze a master HasDependingSlides tulajdonságát először.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel, ha a törlendő master a prezentációban használatban van (a HasDependingSlides tulajdonsága igaz). |

### Lásd még
* osztály [`MasterSlideCollection`](/slides/python-net/hu/aspose.slides/masterslidecollection)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)