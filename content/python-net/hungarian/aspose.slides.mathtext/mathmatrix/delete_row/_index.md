---
title: delete_row method
second_title: Aspose.Slides a Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Törli a megadott sort

```python
def delete_row(self, row_index):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| row_index | **int** | A törlendő sor nulla alapú indexe. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Amikor megpróbálja törölni a mátrix utolsó egyedülálló sorát |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a rowIndex kisebb, mint nulla vagy nagyobb vagy egyenlő a RowCount értékével |

### Lásd még
* osztály [`MathMatrix`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)