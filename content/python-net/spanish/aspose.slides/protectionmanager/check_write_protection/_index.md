---
title: check_write_protection method
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Determina si una presentación está protegida con contraseña para modificarla.

### Devuelve

True si la contraseña es válida; de lo contrario, false.



```python
def check_write_protection(self, password):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | **str** | La contraseña para la verificación. |

### Observaciones

1. Debe comprobar la propiedad [`ProtectionManager.is_write_protected`](/slides/python-net/es/aspose.slides/protectionmanager/is_write_protected) antes de llamar a este método.
            2. Cuando la contraseña es None o está vacía, este método devuelve false.



### Ver también
* clase [`ProtectionManager`](/slides/python-net/es/aspose.slides/protectionmanager)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)