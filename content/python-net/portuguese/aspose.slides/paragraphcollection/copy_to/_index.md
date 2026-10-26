---
title: copy_to method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Copia os elementos de **System.Collections.Generic.ICollection`1** para um **System.Array**, iniciando em um índice específico do **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| array | **List[IParagraph]** | O **System.Array** unidimensional que é o destino dos elementos copiados de **System.Collections.Generic.ICollection`1**. O **System.Array** deve ter indexação baseada em zero. |
| array_index | **int** | O índice baseado em zero em `array` onde a cópia começa. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` é None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` é menor que 0. |
| **RuntimeError(Proxy error(ArgumentException))** | O número de elementos na origem **System.Collections.Generic.ICollection`1** é maior que o espaço disponível entre `array_index` e o final do **System.Array** de destino `array`. |



### Veja Também
* classe [`ParagraphCollection`](/slides/python-net/pt/aspose.slides/paragraphcollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)