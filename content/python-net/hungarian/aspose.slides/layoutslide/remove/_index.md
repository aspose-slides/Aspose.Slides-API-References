---
title: remove method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
Eltávolítja az elrendezést a prezentációból.

```python
def remove(self):
    ...
```

### Megjegyzések
Az PptxEditException dobásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előtte.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel, ha a layout már el lett távolítva a prezentációból, vagy ha a layout a prezentációban van használva (az <br/>            HasDependingSlides tulajdonság igaz). |

### Lásd még
* osztály [`LayoutSlide`](/slides/python-net/hu/aspose.slides/layoutslide)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)