---
title: equals method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ibaseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind.
            Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet.
            Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und weitere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Date Placeholder.

### Rückgabewert

**true**  wenn das angegebene IBaseSlide gleich dem aktuellen IBaseSlide ist; 
            andernfalls **false** .



```python
def equals(self, slide):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide) | Die IBaseSlide, die mit der aktuellen IBaseSlide verglichen wird. |



### Siehe auch
* Klasse [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)