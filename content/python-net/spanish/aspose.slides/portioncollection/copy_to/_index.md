---
title: copy_to method
second_title: Referencia API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Copia los elementos de la **System.Collections.Generic.ICollection`1** a un **System.Array**, comenzando en un índice particular del **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| array | **List[IPortion]** | El **System.Array** unidimensional que es el destino de los elementos copiados de **System.Collections.Generic.ICollection`1**. El **System.Array** debe tener indexación basada en cero. |
| array_index | **int** | El índice basado en cero en `array` donde comienza la copia. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` es None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` es menor que 0. |
| **RuntimeError(Proxy error(ArgumentException))** | El número de elementos en la fuente **System.Collections.Generic.ICollection`1** es mayor que el espacio disponible desde `array_index` hasta el final del `array` de destino. |



### Ver también
* clase [`PortionCollection`](/slides/python-net/es/aspose.slides/portioncollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)