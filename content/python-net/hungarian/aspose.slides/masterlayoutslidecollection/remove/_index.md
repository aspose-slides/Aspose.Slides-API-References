---
title: remove method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
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

1) A PptxEditException dobásának elkerülése érdekében ellenőrizze az elrendezés HasDependingSlides tulajdonságát előtte.  
2) A [`ILayoutSlide.remove`](/slides/python-net/hu/aspose.slides/ilayoutslide/remove) metódus használatával is egyszerűsítheti a kódot.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Dobódik, ha az elrendezést a bemutatóban használják (a HasDependingSlides tulajdonsága igaz). |

### Lásd még
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`MasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)