---
title: copy_to method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Copia gli elementi di **System.Collections.Generic.ICollection`1** in un **System.Array**, a partire da un determinato indice **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| array | **List[IParagraph]** | L'**System.Array** monodimensionale che è la destinazione degli elementi copiati da **System.Collections.Generic.ICollection`1**. L'**System.Array** deve avere un'indicizzazione a base zero. |
| array_index | **int** | L'indice a base zero in `array` a partire dal quale inizia la copia. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` è None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` è minore di 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Il numero di elementi nella sorgente **System.Collections.Generic.ICollection`1** è maggiore dello spazio disponibile da `array_index` fino alla fine dell'`array` di destinazione. |



### Vedi anche
* classe [`ParagraphCollection`](/slides/python-net/it/aspose.slides/paragraphcollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)