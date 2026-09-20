---
title: check_password method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Verifica se una password è corretta per una presentazione protetta con password aperta.

### Valore restituito

True se la presentazione è protetta con password aperta e la password è corretta, altrimenti false.



```python
def check_password(self, password):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | **str** | La password da verificare. |

### Osservazioni

Quando la password è None o vuota, questo metodo restituisce false.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### Vedi anche
* classe [`PresentationInfo`](/slides/python-net/it/aspose.slides/presentationinfo)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)