---
title: remove method
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/ilayoutslidecollection/remove/
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
| value | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | Az elrendezési diát, amelyet el kell távolítani a gyűjteményből. |

### Megjegyzések

1) A PptxEditException dobódásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előtte.
2) Használhatja a [`ILayoutSlide.remove`](/slides/python-net/hu/aspose.slides/ilayoutslide/remove) metódust is a kód egyszerűsítéséhez.

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel, ha az elrendezést a bemutató használja (a HasDependingSlides tulajdonsága igaz). |

### Lásd még
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`ILayoutSlideCollection`](/slides/python-net/hu/aspose.slides/ilayoutslidecollection)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)