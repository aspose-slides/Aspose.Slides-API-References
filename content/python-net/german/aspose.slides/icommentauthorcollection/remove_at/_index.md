---
title: remove_at method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/icommentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
Entfernt den author am angegebenen Index der Sammlung.

```python
def remove_at(self, index):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index des Elements, das entfernt werden soll. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index ist kleiner als 0 oder index ist gleich oder größer als Count |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn author bereits entfernt wurde. |

### Siehe auch
* Klasse [`ICommentAuthorCollection`](/slides/python-net/de/aspose.slides/icommentauthorcollection)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)