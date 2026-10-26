---
title: delete_column method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Elimina la colonna specificata


```python
def delete_column(self, column_index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| column_index | **int** | L'indice a base zero della colonna da eliminare. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando si tenta di eliminare l'ultima colonna singola nella matrice |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Se columnIndex è inferiore a zero o maggiore o uguale a ColumnCount |



### Vedi anche
* classe [`MathMatrix`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)