---
title: copy_to method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Copia os elementos da **System.Collections.Generic.ICollection`1** para um **System.Array**, começando em um índice específico do **System.Array**.

```python
def copy_to(self, array, array_index):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| array | **List[IPortion]** | O **System.Array** unidimensional que é o destino dos elementos copiados de **System.Collections.Generic.ICollection`1**. O **System.Array** deve ter indexação baseada em zero. |
| array_index | **int** | O índice baseado em zero em `array` onde a cópia começa. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` é None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` é menor que 0. |
| **RuntimeError(Proxy error(ArgumentException))** | O número de elementos na origem **System.Collections.Generic.ICollection`1** é maior que o espaço disponível a partir de `array_index` até o final do **System.Array** de destino. |

### Veja Também
* classe [`PortionCollection`](/slides/python-net/pt/aspose.slides/portioncollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)