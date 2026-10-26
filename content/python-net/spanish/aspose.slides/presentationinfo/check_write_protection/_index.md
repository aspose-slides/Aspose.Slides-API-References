---
title: check_write_protection method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Comprueba si una contraseña para modificar es correcta para una presentación protegida contra escritura.

### Devuelve

True si la presentación está protegida contra escritura y la contraseña es correcta. False de lo contrario.



```python
def check_write_protection(self, password):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | **str** | La contraseña a comprobar. |

### Observaciones

1. Debe comprobar la propiedad [`PresentationInfo.is_write_protected`](/slides/python-net/es/aspose.slides/presentationinfo/is_write_protected) antes de llamar a este método.
2. Cuando la contraseña es None o está vacía, este método devuelve false.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Véase también
* clase [`PresentationInfo`](/slides/python-net/es/aspose.slides/presentationinfo)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)