---
title: delete_column method
second_title: Referencia de la API Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Elimina la columna especificada


```python
def delete_column(self, column_index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| column_index | **int** | El índice basado en cero de la columna a eliminar. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Cuando intentas eliminar la última columna única en la matriz |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Si columnIndex es menor que cero o mayor o igual que ColumnCount |



### Ver también
* clase [`MathMatrix`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)