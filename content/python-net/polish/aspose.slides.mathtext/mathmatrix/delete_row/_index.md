---
title: delete_row method
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Usuwa określony wiersz


```python
def delete_row(self, row_index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| row_index | **int** | Zero-indeksowy indeks wiersza do usunięcia. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gdy próbujesz usunąć jedyny ostatni wiersz w macierzy |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Jeśli rowIndex jest mniejszy niż zero lub większy lub równy RowCount |



### Zobacz także
* klasa [`MathMatrix`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)