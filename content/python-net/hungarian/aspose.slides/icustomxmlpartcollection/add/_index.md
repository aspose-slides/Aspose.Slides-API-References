---
title: add method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
Új egyéni xml részt ad hozzá.

### Returns

Létrehozott egyéni xml rész.



```python
def add(self, xml_data):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| xml_data | **bytes** | Az új részhez hozzáadandó xml adat. |

### Exceptions

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData üres vagy érvénytelen. |


## add(self, xml_string) {#str}
Új egyéni xml részt ad hozzá.

### Returns

Létrehozott egyéni xml rész.



```python
def add(self, xml_string):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| xml_string | **str** | Az új részhez hozzáadandó xml karakterlánc. |

### Exceptions

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString üres vagy xml-adat érvénytelen. |


## add(self, input_stream) {#iorawiobase}
Új egyéni xml részt ad hozzá.

### Returns

Létrehozott egyéni xml rész.



```python
def add(self, input_stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Az új részhez hozzáadandó xml adatot tartalmazó inputStream. |

### Exceptions

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Az inputStream adatai üresek vagy érvénytelenek. |



### See Also
* osztály [`ICustomXmlPart`](/slides/python-net/hu/aspose.slides/icustomxmlpart)
* osztály [`ICustomXmlPartCollection`](/slides/python-net/hu/aspose.slides/icustomxmlpartcollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)