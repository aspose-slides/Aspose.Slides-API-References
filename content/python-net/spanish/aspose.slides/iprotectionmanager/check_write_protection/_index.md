---
title: check_write_protection method
second_title: Referencia de la API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Determina si una presentación está protegida con contraseña para modificarla.

### Returns

True si la contraseña es válida; de lo contrario, false.



```python
def check_write_protection(self, password):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | **str** | La contraseña para la verificación. |

### Remarks

1. Debe comprobar la [`IProtectionManager.is_write_protected`](/slides/python-net/es/aspose.slides/iprotectionmanager/is_write_protected) propiedad antes de llamar a este método.
2. Cuando la contraseña es None o está vacía, este método devuelve false.



### See Also
* clase [`IProtectionManager`](/slides/python-net/es/aspose.slides/iprotectionmanager)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)