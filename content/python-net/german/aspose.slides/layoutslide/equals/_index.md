---
title: equals method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/layoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind.  
Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet.  
Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Identifier-Werte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Date Placeholder.

### Rückgabewert

**true**  wenn das angegebene IBaseSlide dem aktuellen IBaseSlide gleich ist; andernfalls **false** .

```python
def equals(self, slide):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide) | Das IBaseSlide, das mit dem aktuellen IBaseSlide verglichen wird. |

### Siehe Auch
* Klasse [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide)
* Klasse [`LayoutSlide`](/slides/python-net/de/aspose.slides/layoutslide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)