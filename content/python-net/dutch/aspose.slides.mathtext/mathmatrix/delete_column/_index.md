---
title: delete_column method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Verwijdert de opgegeven kolom


```python
def delete_column(self, column_index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| column_index | **int** | De nulgebaseerde index van de te verwijderen kolom. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wanneer u probeert de laatste enkele kolom in de matrix te verwijderen |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Als columnIndex kleiner is dan nul of groter dan of gelijk aan ColumnCount |



### Zie ook
* klasse [`MathMatrix`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)