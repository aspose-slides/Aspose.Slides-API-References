---
title: get_text_boxes_contains_text method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
Returnerar alla textramar på den angivna bilden som innehåller den angivna texten.

### Returnerar

En array av [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe) objekt som innehåller den specificerade texten.



```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide) | Bild att söka i. |
| text | **str** | Texten att söka efter i textramar. |
| check_placeholder_text | **bool** | Anger om textramar som är tomma, men vars platshållartext innehåller söktexten, ska inkluderas. |



### Se även
* klass [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide)
* klass [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe)
* klass [`SlideUtil`](/slides/python-net/sv/aspose.slides.util/slideutil)
* modul [`aspose.slides.util`](/slides/python-net/sv/aspose.slides.util)
* bibliotek [`Aspose.Slides`](/slides/python-net)