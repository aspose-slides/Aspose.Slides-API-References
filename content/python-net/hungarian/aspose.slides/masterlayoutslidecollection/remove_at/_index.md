---
title: remove_at method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Eltávolítja az elemet a gyűjtemény megadott indexén.


```python
def remove_at(self, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az eltávolítandó elem nulla-alapú indexe. |

### Megjegyzések

1) A PptxEditException dobásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előtte.
2) A [`ILayoutSlide.remove`](/slides/python-net/hu/aspose.slides/ilayoutslide/remove) metódus is használható a kód egyszerűsítéséhez.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel, ha a layout a prezentációban van használva (a HasDependingSlides tulajdonsága igaz). |



### Lásd még
* osztály [`MasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)