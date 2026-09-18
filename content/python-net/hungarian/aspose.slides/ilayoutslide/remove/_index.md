---
title: remove method
second_title: Aspose.Slides Pythonra a .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
Eltávolítja az elrendezést a prezentációból.

```python
def remove(self):
    ...
```

### Megjegyzés

A PptxEditException dobásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előtte.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel akkor dobódik, ha az elrendezés már el lett távolítva a prezentációból, vagy ha az elrendezést a prezentáció használja (a <br/>            HasDependingSlides tulajdonsága igaz). |

### Lásd még
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)