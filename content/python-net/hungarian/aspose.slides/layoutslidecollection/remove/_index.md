---
title: remove method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Eltávolít egy elrendezést a gyűjteményből.

```python
def remove(self, value):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | Az elrendezésdia, amelyet el kell távolítani a gyűjteményből. |

### Megjegyzések

1) Az PptxEditException dobásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előtte.
            2) Az [`ILayoutSlide.remove`](/slides/python-net/hu/aspose.slides/ilayoutslide/remove) metódust is használhatja a kód egyszerűsítéséhez.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel, ha a layout a bemutatóban van használva (a HasDependingSlides tulajdonsága true). |

### Lásd még
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`LayoutSlideCollection`](/slides/python-net/hu/aspose.slides/layoutslidecollection)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)