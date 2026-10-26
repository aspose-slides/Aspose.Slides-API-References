---
title: check_write_protection method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Verifica se una password per modificare è corretta per una presentazione protetta da scrittura.

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

1. Dovresti controllare la proprietà [`IPresentationInfo.is_write_protected`](/slides/python-net/it/aspose.slides/ipresentationinfo/is_write_protected) prima di chiamare questo metodo.
2. Quando la password è None o vuota, questo metodo restituisce false.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Vedi anche
* classe [`IPresentationInfo`](/slides/python-net/it/aspose.slides/ipresentationinfo)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)