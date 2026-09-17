---
title: get_font_embedding_level method
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description:
type: docs
url: /es/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Determina el nivel de incrustación de una fuente a partir del array de bytes y el nombre de la fuente.

### Devuelve

El nivel de incrustación de la fuente especificada.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_bytes | **bytes** | El array de bytes que contiene los datos de la fuente. |
| font_name | **str** | El nombre de la fuente. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lanzada cuando `font_bytes` es None. |



### Ver también
* enumeración [`EmbeddingLevel`](/slides/python-net/es/aspose.slides/embeddinglevel)
* clase [`FontsManager`](/slides/python-net/es/aspose.slides/fontsmanager)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)