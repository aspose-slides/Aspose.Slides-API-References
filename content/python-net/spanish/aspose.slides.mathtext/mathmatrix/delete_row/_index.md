---
title: delete_row method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Elimina la fila especificada


```python
def delete_row(self, row_index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| row_index | **int** | El índice basado en cero de la fila a eliminar. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Cuando intentas eliminar la última fila única de la matriz |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Si rowIndex es menor que cero o mayor o igual que RowCount |



### Ver también
* clase [`MathMatrix`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)