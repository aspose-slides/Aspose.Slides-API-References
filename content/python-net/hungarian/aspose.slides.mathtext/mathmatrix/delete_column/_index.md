---
title: delete_column method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Törli a megadott oszlopot


```python
def delete_column(self, column_index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| column_index | **int** | A nulla alapú indexe a törlendő oszlopnak. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Amikor megpróbálja törölni a mátrixban az egyetlen oszlopot |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a columnIndex kisebb, mint nulla, vagy nagyobb vagy egyenlő a ColumnCount-nál |



### Lásd még
* osztály [`MathMatrix`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)