---
title: check_write_protection method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Verifica se la password per la modifica è corretta per una presentazione protetta da scrittura.

### Restituisce
True se la presentazione è protetta da scrittura e la password è corretta. False altrimenti.



```python
def check_write_protection(self, password):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | **str** | La password da verificare. |

### Osservazioni
1. È consigliabile verificare la proprietà [`PresentationInfo.is_write_protected`](/slides/python-net/it/aspose.slides/presentationinfo/is_write_protected) prima di chiamare questo metodo.
2. Quando password è None o vuota, questo metodo restituisce false.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Vedi anche
* classe [`PresentationInfo`](/slides/python-net/it/aspose.slides/presentationinfo)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)