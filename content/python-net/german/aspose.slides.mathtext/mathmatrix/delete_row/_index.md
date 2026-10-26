---
title: delete_row method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Löscht die angegebene Zeile


```python
def delete_row(self, row_index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| row_index | **int** | Der Null-basierte Index der zu löschenden Zeile. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wenn versucht wird, die letzte einzelne Zeile in der Matrix zu löschen |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wenn rowIndex kleiner als Null oder größer oder gleich dem RowCount ist |



### Siehe auch
* Klasse [`MathMatrix`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)