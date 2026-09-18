---
title: delete_column method
second_title: Aspose.Slides dla Pythona w .NET – odniesienie do API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Usuwa określoną kolumnę


```python
def delete_column(self, column_index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| column_index | **int** | Indeks (liczony od zera) kolumny do usunięcia. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gdy próbujesz usunąć jedyną ostatnią kolumnę w macierzy |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Jeśli columnIndex jest mniejszy niż zero lub większy lub równy ColumnCount |



### Zobacz także
* klasa [`MathMatrix`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)