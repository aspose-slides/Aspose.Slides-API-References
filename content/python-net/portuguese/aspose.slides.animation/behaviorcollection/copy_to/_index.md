---
title: copy_to method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
Copia os elementos da **System.Collections.Generic.ICollection`1** para um **System.Array**, começando em um índice específico de **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| array | **List[IBehavior]** | O **System.Array** unidimensional que é o destino dos elementos copiados de **System.Collections.Generic.ICollection`1**. O **System.Array** deve ter indexação baseada em zero. |
| array_index | **int** | O índice baseado em zero em `array` onde a cópia começa. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` é None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` é menor que 0. |
| **RuntimeError(Proxy error(ArgumentException))** | O número de elementos na fonte **System.Collections.Generic.ICollection`1** é maior que o espaço disponível a partir de `array_index` até o final do `array` de destino. |



### Veja Também
* classe [`BehaviorCollection`](/slides/python-net/pt/aspose.slides.animation/behaviorcollection)
* módulo [`aspose.slides.animation`](/slides/python-net/pt/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)