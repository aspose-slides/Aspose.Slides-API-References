---
title: add method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
Agrega una nueva parte xml personalizada.

### Devuelve

Parte xml personalizada creada.



```python
def add(self, xml_string):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| xml_string | **str** | La cadena xml de la nueva parte a agregar. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString es `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString está vacío o los datos xml son inválidos. |


## add(self, xml_data) {#bytes}
Agrega una nueva parte xml personalizada.

### Devuelve

Parte xml personalizada creada.



```python
def add(self, xml_data):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| xml_data | **bytes** | Los datos xml de la nueva parte a agregar. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData es `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData está vacío o es inválido. |


## add(self, input_stream) {#iorawiobase}
Agrega una nueva parte xml personalizada.

### Devuelve

Parte xml personalizada creada.



```python
def add(self, input_stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | El inputStream con datos xml de la nueva parte a agregar. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream es `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Los datos en inputStream están vacíos o son inválidos. |



### Ver también
* clase [`CustomXmlPartCollection`](/slides/python-net/es/aspose.slides/customxmlpartcollection)
* clase [`ICustomXmlPart`](/slides/python-net/es/aspose.slides/icustomxmlpart)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)