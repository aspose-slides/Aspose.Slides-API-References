---
title: set_metered_key method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
Establece la clave pública y privada medida.
            Si compra una licencia medida, al iniciar la aplicación, debe llamarse a esta API; normalmente, eso es suficiente. 
            Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación, 
            para evitar tal caso, debe comprobar regularmente el estado de la licencia; si está en estado de evaluación, llame a esta API nuevamente.


```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| public_key | **str** | clave pública |
| private_key | **str** | clave privada |



### Ver también
* clase [`Metered`](/slides/python-net/es/aspose.slides/metered)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)