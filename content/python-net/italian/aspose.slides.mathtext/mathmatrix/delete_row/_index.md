---
title: delete_row method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Elimina la riga specificata


```python
def delete_row(self, row_index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| row_index | **int** | L'indice basato su zero della riga da eliminare. |

### Eccezioni

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando si tenta di eliminare l'ultima riga singola nella matrice |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Se rowIndex è minore di zero o maggiore o uguale a RowCount |



### Vedi anche
* classe [`MathMatrix`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)