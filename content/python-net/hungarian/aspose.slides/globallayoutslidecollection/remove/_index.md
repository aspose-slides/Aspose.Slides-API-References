---
title: remove method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
Eltávolít egy elrendezést a gyűjteményből.

```python
def remove(self, value):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | Az elrendezési dia, amelyet el kell távolítani a gyűjteményből. |

### Megjegyzések

1) A PptxEditException dobásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előzőleg.
2) Használhatja a(z) [`ILayoutSlide.remove`](/slides/python-net/hu/aspose.slides/ilayoutslide/remove) metódust is a kód egyszerűsítéséhez.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel, ha az elrendezést a prezentációban használják (a HasDependingSlides tulajdonsága true). |

### Lásd még
* osztály [`GlobalLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection)
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)