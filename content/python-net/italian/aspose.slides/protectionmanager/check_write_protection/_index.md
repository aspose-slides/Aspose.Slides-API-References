---
title: check_write_protection method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Determina se una presentazione è protetta da password per la modifica.

### Restituisce

True se la password è valida; altrimenti, false.



```python
def check_write_protection(self, password):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | **str** | La password per il controllo. |

### Osservazioni

1. È consigliabile verificare la proprietà [`ProtectionManager.is_write_protected`](/slides/python-net/it/aspose.slides/protectionmanager/is_write_protected) prima di chiamare questo metodo.
2. Quando la password è None o vuota, questo metodo restituisce false.



### Vedi anche
* classe [`ProtectionManager`](/slides/python-net/it/aspose.slides/protectionmanager)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)