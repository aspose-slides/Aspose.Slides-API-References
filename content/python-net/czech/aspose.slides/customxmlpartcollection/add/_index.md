---
title: add method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
Přidá novou vlastní část XML.

### Vrací

Vytvořená vlastní část XML.



```python
def add(self, xml_string):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| xml_string | **str** | Řetězec XML nové části, která se má přidat. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString je `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString je prázdný nebo xml-data jsou neplatná. |


## add(self, xml_data) {#bytes}
Přidá novou vlastní část XML.

### Vrací

Vytvořená vlastní část XML.



```python
def add(self, xml_data):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| xml_data | **bytes** | Data XML nové části, která se má přidat. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData je `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData je prázdná nebo neplatná. |


## add(self, input_stream) {#iorawiobase}
Přidá novou vlastní část XML.

### Vrací

Vytvořená vlastní část XML.



```python
def add(self, input_stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Vstupní proud s xml daty nové části, která se má přidat. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream je `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Data v inputStream jsou prázdná nebo neplatná. |



### Viz také
* třída [`CustomXmlPartCollection`](/slides/python-net/cs/aspose.slides/customxmlpartcollection)
* třída [`ICustomXmlPart`](/slides/python-net/cs/aspose.slides/icustomxmlpart)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)