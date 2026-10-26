---
title: remove_at method
second_title: Aspose.Slides für Python über .NET API Referenz
description: 
type: docs
url: /de/aspose.slides/commentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
Entfernt den Autor am angegebenen Index der Sammlung.


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
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn der Autor bereits entfernt wurde. |



### Siehe auch
* Klasse [`CommentAuthorCollection`](/slides/python-net/de/aspose.slides/commentauthorcollection)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)