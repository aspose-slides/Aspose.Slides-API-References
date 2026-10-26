---
title: add method
second_title: Aspose.Slides dla Pythona przez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
Dodaje nową niestandardową część xml.

### Zwraca

Utworzono niestandardową część xml.



```python
def add(self, xml_data):
    ...
```


| Parameter | Typ | Opis |
| :- | :- | :- |
| xml_data | **bytes** | Dane xml nowej części, które mają zostać dodane. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData jest `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData jest pusty lub nieprawidłowy. |


## add(self, xml_string) {#str}
Dodaje nową niestandardową część xml.

### Zwraca

Utworzono niestandardową część xml.



```python
def add(self, xml_string):
    ...
```


| Parameter | Typ | Opis |
| :- | :- | :- |
| xml_string | **str** | Ciąg xml nowej części, który ma zostać dodany. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString jest `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString jest pusty lub dane xml są nieprawidłowe. |


## add(self, input_stream) {#iorawiobase}
Dodaje nową niestandardową część xml.

### Zwraca

Utworzono niestandardową część xml.



```python
def add(self, input_stream):
    ...
```


| Parameter | Typ | Opis |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Strumień wejściowy z danymi xml nowej części, które mają zostać dodane. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream jest `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Dane w inputStream są puste lub Sinvalid. |



### Zobacz także
* klasa [`ICustomXmlPart`](/slides/python-net/pl/aspose.slides/icustomxmlpart)
* klasa [`ICustomXmlPartCollection`](/slides/python-net/pl/aspose.slides/icustomxmlpartcollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)