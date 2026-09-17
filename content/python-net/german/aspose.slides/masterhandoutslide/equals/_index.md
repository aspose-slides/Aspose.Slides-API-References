---
title: equals method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masterhandoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind.
            Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet.
            Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und sonstigen Einstellungen usw. gleich sind. Der Vergleich berücksichtigt nicht eindeutige Bezeichnerwerte, z. B. SlideId, und dynamischen Inhalt, z. B. den aktuellen Datumswert im Datums-Platzhalter.

### Rückgabewert

**true**  wenn die angegebene IBaseSlide der aktuellen IBaseSlide entspricht; 
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
* Klasse [`MasterHandoutSlide`](/slides/python-net/de/aspose.slides/masterhandoutslide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)