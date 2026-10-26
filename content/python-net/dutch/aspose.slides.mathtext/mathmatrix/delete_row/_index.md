---
title: delete_row method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Verwijdert de opgegeven rij


```python
def delete_row(self, row_index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| row_index | **int** | De nul-gebaseerde index van de rij die moet worden verwijderd. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wanneer je probeert de laatste enkele rij in de matrix te verwijderen |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Als rowIndex kleiner is dan nul of groter dan of gelijk aan de RowCount |



### Zie ook
* klasse [`MathMatrix`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)