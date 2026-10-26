---
title: check_write_protection method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Comprueba si la contraseña para modificar es correcta en una presentación protegida contra escritura.

### Devuelve

True si la presentación está protegida contra escritura y la contraseña es correcta. False en caso contrario.



```python
def check_write_protection(self, password):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| password | **str** | La contraseña a verificar. |

### Observaciones

1. Debe comprobar la [`IPresentationInfo.is_write_protected`](/slides/python-net/es/aspose.slides/ipresentationinfo/is_write_protected) propiedad antes de llamar a este método.
2. Cuando la contraseña es None o está vacía, este método devuelve false.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Ver también
* clase [`IPresentationInfo`](/slides/python-net/es/aspose.slides/ipresentationinfo)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)