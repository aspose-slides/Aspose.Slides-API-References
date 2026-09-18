---
title: add method
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
Dodaje nową niestandardową część xml.

### Zwraca

Utworzono niestandardową część xml.



```python
def add(self, xml_string):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| xml_string | **str** | Ciąg znaków xml nowej części do dodania. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString jest `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString jest pusty lub dane xml są nieprawidłowe. |


## add(self, xml_data) {#bytes}
Dodaje nową niestandardową część xml.

### Zwraca

Utworzono niestandardową część xml.



```python
def add(self, xml_data):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| xml_data | **bytes** | Dane xml nowej części do dodania. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData jest `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData jest pusty lub nieprawidłowy. |


## add(self, input_stream) {#iorawiobase}
Dodaje nową niestandardową część xml.

### Zwraca

Utworzono niestandardową część xml.



```python
def add(self, input_stream):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Strumień wejściowy zawierający dane xml nowej części do dodania. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream jest `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Dane w inputStream są puste lub nieprawidłowe. |



### Zobacz także
* klasa [`CustomXmlPartCollection`](/slides/python-net/pl/aspose.slides/customxmlpartcollection)
* klasa [`ICustomXmlPart`](/slides/python-net/pl/aspose.slides/icustomxmlpart)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)