---
title: get_text_rect method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/textframe/get_text_rect/
weight: 10
---
## get_text_rect(self) {#}
Obtiene el rectángulo de texto definido por la geometría de la forma padre.

### Devuelve

Un [`RectangleF`](/slides/python-net/es/aspose.slides/rectanglef) que define el área de texto.



```python
def get_text_rect(self):
    ...
```


### Observaciones

Las coordenadas del rectángulo son relativas a la esquina superior izquierda de la forma padre.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | El marco de texto no está asociado a una forma de geometría. |



### Ver también
* class [`TextFrame`](/slides/python-net/es/aspose.slides/textframe)
* class [`RectangleF`](/slides/python-net/es/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)