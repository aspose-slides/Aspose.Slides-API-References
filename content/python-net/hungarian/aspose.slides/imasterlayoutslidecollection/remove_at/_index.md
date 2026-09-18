---
title: remove_at method
second_title: Aspose.Slides Pythonhoz a .NET API-n keresztül
description: 
type: docs
url: /hu/aspose.slides/imasterlayoutslidecollection/remove_at/
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
| index | **int** | A nullától kezdődő index, amelyen az eltávolítandó elem található. |

### Megjegyzés

1) A PptxEditException dobásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előre.  
2) A [`ILayoutSlide.remove`](/slides/python-net/hu/aspose.slides/ilayoutslide/remove) metódus is használható a kód egyszerűsítéséhez.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel akkor dobódik, ha a layout a prezentációban van használva (a HasDependingSlides tulajdonsága igaz). |

### Lásd még
* osztály [`IMasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/imasterlayoutslidecollection)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)