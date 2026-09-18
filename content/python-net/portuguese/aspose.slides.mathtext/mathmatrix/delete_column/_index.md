---
title: delete_column method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Exclui a coluna especificada


```python
def delete_column(self, column_index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| column_index | **int** | O índice baseado em zero da coluna a ser excluída. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando você tenta excluir a última coluna única da matriz |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Se columnIndex for menor que zero ou maior ou igual ao ColumnCount |



### Veja Também
* classe [`MathMatrix`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)