---
title: delete_row method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Exclui a linha especificada


```python
def delete_row(self, row_index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| row_index | **int** | O índice baseado em zero da linha a ser excluída. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando você tenta excluir a última linha única na matriz |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Se rowIndex for menor que zero ou maior ou igual ao RowCount |



### Veja Também
* classe [`MathMatrix`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)