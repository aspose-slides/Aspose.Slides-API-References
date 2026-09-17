---
title: add method
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
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
| xml_data | **bytes** | Los datos xml de la nueva parte que se va a agregar. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData es `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData está vacío o no es válido. |


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
| xml_string | **str** | La cadena xml de la nueva parte que se va a agregar. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString es `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString está vacío o los datos xml no son válidos. |


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
| input_stream | **io.RawIOBase** | El inputStream con los datos xml de la nueva parte que se va a agregar. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream es `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Los datos en inputStream están vacíos o Sinvalid. |



### Ver también
* clase [`ICustomXmlPart`](/slides/python-net/es/aspose.slides/icustomxmlpart)
* clase [`ICustomXmlPartCollection`](/slides/python-net/es/aspose.slides/icustomxmlpartcollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)