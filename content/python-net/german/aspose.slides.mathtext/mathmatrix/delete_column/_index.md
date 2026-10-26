---
title: delete_column method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Löscht die angegebene Spalte


```python
def delete_column(self, column_index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| column_index | **int** | Der nullbasierte Index der zu löschenden Spalte. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wenn Sie versuchen, die letzte einzelne Spalte in der Matrix zu löschen |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Wenn columnIndex kleiner als null oder größer oder gleich der ColumnCount ist |



### Siehe auch
* Klasse [`MathMatrix`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)