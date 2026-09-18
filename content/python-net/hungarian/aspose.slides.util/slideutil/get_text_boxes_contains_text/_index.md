---
title: get_text_boxes_contains_text method
second_title: Aspose.Slides Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
Visszaadja az adott dián az összes szövegdobozt, amely a megadott szöveget tartalmazza.

### Visszatérési érték

A megadott szöveget tartalmazó [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe) objektumok tömbje.



```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide) | A keresendő dia. |
| text | **str** | A szöveg, amelyet a szövegdobozokban keresünk. |
| check_placeholder_text | **bool** | Jelzi, hogy bele kell-e vonni a szövegdobozokat, amelyek üresek, de a helyőrző szövegük tartalmazza a keresett szöveget. |



### Lásd még
* osztály [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide)
* osztály [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe)
* osztály [`SlideUtil`](/slides/python-net/hu/aspose.slides.util/slideutil)
* modul [`aspose.slides.util`](/slides/python-net/hu/aspose.slides.util)
* library [`Aspose.Slides`](/slides/python-net)