---
title: get_text_boxes_contains_text method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
Gibt alle Textrahmen auf der angegebenen Folie zurück, die den angegebenen Text enthalten.

### Rückgabe

Ein Array von [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe)-Objekten, die den angegebenen Text enthalten.



```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide) | Die Folie, die durchsucht werden soll. |
| text | **str** | Der zu suchende Text innerhalb von Textrahmen. |
| check_placeholder_text | **bool** | Gibt an, ob leere Textrahmen mit Platzhaltertext, der den Suchtext enthält, einbezogen werden sollen. |



### Siehe auch
* Klasse [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide)
* Klasse [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe)
* Klasse [`SlideUtil`](/slides/python-net/de/aspose.slides.util/slideutil)
* Modul [`aspose.slides.util`](/slides/python-net/de/aspose.slides.util)
* Bibliothek [`Aspose.Slides`](/slides/python-net)