---
title: check_password method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Comprueba si una contraseña es correcta para una presentación protegida con contraseña abierta.

### Devuelve

True si la presentación está protegida con contraseña abierta y la contraseña es correcta y false en caso contrario.



```python
def check_password(self, password):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | **str** | La contraseña a comprobar. |

### Observaciones

Cuando la contraseña es None o está vacía, este método devuelve false.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### Véase también
* clase [`PresentationInfo`](/slides/python-net/es/aspose.slides/presentationinfo)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)