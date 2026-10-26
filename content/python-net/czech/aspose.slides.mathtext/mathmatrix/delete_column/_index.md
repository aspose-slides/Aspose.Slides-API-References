---
title: delete_column method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Odstraní zadaný sloupec

```python
def delete_column(self, column_index):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| column_index | **int** | Nulový index sloupce, který se má smazat. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Když se pokusíte odstranit poslední jediný sloupec v matici |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Pokud je columnIndex menší než nula nebo větší nebo rovno ColumnCount |

### Viz také
* třída [`MathMatrix`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)