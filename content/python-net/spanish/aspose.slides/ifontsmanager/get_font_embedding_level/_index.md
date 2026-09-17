---
title: get_font_embedding_level method
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/ifontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Determina el nivel de incrustación de una fuente a partir de la matriz de bytes y el nombre de la fuente proporcionados.

### Devuelve

El nivel de incrustación de la fuente especificada.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_bytes | **bytes** | La matriz de bytes que contiene los datos de la fuente. |
| font_name | **str** | El nombre de la fuente. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Se lanza cuando `font_bytes` es None. |



### Ver también
* enumeration [`EmbeddingLevel`](/slides/python-net/es/aspose.slides/embeddinglevel)
* class [`IFontsManager`](/slides/python-net/es/aspose.slides/ifontsmanager)
* module [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)