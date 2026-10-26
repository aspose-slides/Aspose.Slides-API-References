---
title: delete_row method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Odstraní zadaný řádek


```python
def delete_row(self, row_index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| row_index | **int** | Nulový index řádku, který má být smazán. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Když se pokusíte smazat poslední jediný řádek v matici |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Pokud je rowIndex menší než nula nebo větší nebo roven RowCount |



### Viz také
* třída [`MathMatrix`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)