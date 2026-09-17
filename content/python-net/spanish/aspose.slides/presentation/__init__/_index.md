---
title: Presentation constructor
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Este constructor crea una nueva presentación desde cero.
            La presentación creada tiene una diapositiva vacía.


```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
Este constructor crea una nueva presentación desde cero.
            La presentación creada tiene una diapositiva vacía.


```python
def __init__(self, load_options):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/es/aspose.slides/loadoptions) | Opciones de carga adicionales. |


## __init__(self, stream) {#iorawiobase}
Este constructor es el mecanismo principal para leer una Presentación existente.


```python
def __init__(self, stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo de entrada. |


## __init__(self, file) {#str}
Este constructor obtiene la ruta del archivo fuente desde la cual
             se leen los contenidos de la Presentación.


```python
def __init__(self, file):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file | **str** | Archivo de entrada. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando el archivo de entrada tiene longitud cero |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Este constructor es el mecanismo principal para leer una Presentación existente.


```python
def __init__(self, stream, load_options):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo de entrada. |
| load_options | [`LoadOptions`](/slides/python-net/es/aspose.slides/loadoptions) | Opciones de carga adicionales. |


## __init__(self, file, load_options) {#str-loadoptions}
Este constructor obtiene la ruta del archivo fuente desde la cual
            se leen los contenidos de la Presentación.


```python
def __init__(self, file, load_options):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file | **str** | Archivo de entrada. |
| load_options | [`LoadOptions`](/slides/python-net/es/aspose.slides/loadoptions) | Opciones de carga adicionales. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando el archivo de entrada tiene longitud cero |



### Ver también
* clase [`LoadOptions`](/slides/python-net/es/aspose.slides/loadoptions)
* clase [`Presentation`](/slides/python-net/es/aspose.slides/presentation)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)