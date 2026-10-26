---
title: add method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Añade subtítulos WebVTT cerrados al final de la colección.

### Devuelve

La instancia [`ICaptions`](/slides/python-net/es/aspose.slides/icaptions) añadida.



```python
def add(self, label, file_path):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| label | **str** | La etiqueta de los subtítulos cerrados. |
| file_path | **str** | La ruta al archivo WebVTT. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Se lanza si `file_path` es `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza si `file_path` está vacío. |


## add(self, label, stream) {#str-iorawiobase}
Añade subtítulos WebVTT cerrados al final de la colección desde un flujo.

### Devuelve

La instancia [`ICaptions`](/slides/python-net/es/aspose.slides/icaptions) añadida.



```python
def add(self, label, stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| label | **str** | La etiqueta de los subtítulos cerrados. |
| stream | **io.RawIOBase** | El flujo de entrada que contiene datos en formato WebVTT. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Se lanza si `stream` es `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza si los datos de entrada no están en formato WebVTT. |



### Ver también
* clase [`ICaptions`](/slides/python-net/es/aspose.slides/icaptions)
* clase [`ICaptionsCollection`](/slides/python-net/es/aspose.slides/icaptionscollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)