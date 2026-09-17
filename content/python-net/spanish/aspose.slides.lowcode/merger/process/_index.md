---
title: process method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Combina varias presentaciones de PowerPoint del mismo formato en un único archivo de presentación.


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| input_file_names | **List[str]** | Una matriz con los nombres de los archivos de presentación de entrada. |
| output_file_name | **str** | El nombre del archivo de salida de la presentación combinada resultante. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando los nombres de archivo de entrada son inválidos o los formatos no coinciden. |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
Combina varias presentaciones de PowerPoint del mismo formato en un único archivo de presentación.


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| input_file_names | **List[str]** | Una matriz con los nombres de los archivos de presentación de entrada. |
| output_stream | **io.RawIOBase** | El flujo de salida. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando los nombres de archivo de entrada son inválidos o los formatos no coinciden. |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Combina varias presentaciones de PowerPoint del mismo formato en un único archivo de presentación.


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| input_file_names | **List[str]** | Una matriz con los nombres de los archivos de presentación de entrada. |
| output_file_name | **str** | El nombre del archivo de salida de la presentación combinada resultante. |
| options | [`ISaveOptions`](/slides/python-net/es/aspose.slides.export/isaveoptions) | Las opciones adicionales que definen cómo se guarda la presentación combinada. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando los nombres de archivo de entrada son inválidos o los formatos no coinciden. |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Combina varias presentaciones de PowerPoint del mismo formato en un único archivo de presentación.


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| input_file_names | **List[str]** | Una matriz con los nombres de los archivos de presentación de entrada. |
| output_stream | **io.RawIOBase** | El flujo de salida. |
| options | [`ISaveOptions`](/slides/python-net/es/aspose.slides.export/isaveoptions) | Las opciones adicionales que definen cómo se guarda la presentación combinada. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando los nombres de archivo de entrada son inválidos o los formatos no coinciden. |



### Ver también
* clase [`ISaveOptions`](/slides/python-net/es/aspose.slides.export/isaveoptions)
* clase [`Merger`](/slides/python-net/es/aspose.slides.lowcode/merger)
* módulo [`aspose.slides.lowcode`](/slides/python-net/es/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)