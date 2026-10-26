---
title: remove_at method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/icommentcollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Entfernt das Element am angegebenen Index in einer Sammlung.

```python
def remove_at(self, index):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index des zu entfernenden Elements. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index ist kleiner als 0 oder Index ist gleich oder größer als Count |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn der Kommentar bereits entfernt wurde. |

### Siehe auch
* Klasse [`ICommentCollection`](/slides/python-net/de/aspose.slides/icommentcollection)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)