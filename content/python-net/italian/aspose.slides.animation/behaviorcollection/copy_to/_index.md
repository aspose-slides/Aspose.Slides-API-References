---
title: copy_to method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
Copia gli elementi di **System.Collections.Generic.ICollection`1** in un **System.Array**, iniziando da un indice specifico di **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| array | **List[IBehavior]** | L'**System.Array** monodimensionale che è la destinazione degli elementi copiati da **System.Collections.Generic.ICollection`1**. L'**System.Array** deve avere un'indicizzazione a base zero. |
| array_index | **int** | L'indice a base zero in `array` da cui inizia la copia. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` è None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` è inferiore a 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Il numero di elementi nella sorgente **System.Collections.Generic.ICollection`1** è maggiore dello spazio disponibile da `array_index` fino alla fine dell'`array` di destinazione. |



### Vedi anche
* classe [`BehaviorCollection`](/slides/python-net/it/aspose.slides.animation/behaviorcollection)
* modulo [`aspose.slides.animation`](/slides/python-net/it/aspose.slides.animation)
* libreria [`Aspose.Slides`](/slides/python-net)