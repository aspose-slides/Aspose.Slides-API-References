---
title: check_write_protection method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/iprotectionmanager/check_write_protection/
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
| password | **str** | La password per la verifica. |

### Osservazioni

1. Dovresti controllare la proprietà [`IProtectionManager.is_write_protected`](/slides/python-net/it/aspose.slides/iprotectionmanager/is_write_protected) prima di chiamare questo metodo.
            2. Quando la password è None o vuota, questo metodo restituisce false.

### Vedi anche
* classe [`IProtectionManager`](/slides/python-net/it/aspose.slides/iprotectionmanager)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)