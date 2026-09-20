---
title: copy_to method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Copia gli elementi della **System.Collections.Generic.ICollection`1** in un **System.Array**, iniziando a un indice specifico del **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| array | **List[IPortion]** | Il **System.Array** monodimensionale che è la destinazione degli elementi copiati da **System.Collections.Generic.ICollection`1**. Il **System.Array** deve avere un indicizzamento basato su zero. |
| array_index | **int** | L'indice basato su zero in `array` al quale inizia la copia. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` è None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` è minore di 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Il numero di elementi nella **System.Collections.Generic.ICollection`1** di origine è maggiore dello spazio disponibile dall'`array_index` fino alla fine del **System.Array** di destinazione. |



### Vedi anche
* classe [`PortionCollection`](/slides/python-net/it/aspose.slides/portioncollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)