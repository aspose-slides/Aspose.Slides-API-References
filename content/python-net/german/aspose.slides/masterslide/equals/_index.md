---
title: equals method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masterslide/equals/
weight: 30
---
## equals(self, slide) {#ibaseslide}
Ermittelt, ob die beiden IBaseSlide-Instanzen gleich sind.
Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet.
Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und sonstigen Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Datums-Platzhalter.

### Rückgabewert

**true**  wenn das angegebene IBaseSlide dem aktuellen IBaseSlide entspricht; sonst **false** .


```python
def equals(self, slide):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide) | Das IBaseSlide, das mit dem aktuellen IBaseSlide verglichen wird. |

### Siehe auch
* Klasse [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide)
* Klasse [`MasterSlide`](/slides/python-net/de/aspose.slides/masterslide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)