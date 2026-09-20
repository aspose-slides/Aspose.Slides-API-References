---
title: add method
second_title: Aspose.Slides pro Python prostřednictvím .NET referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
Přidá novou vlastní část XML.

### Návratová hodnota

Vytvořená vlastní část XML.



```python
def add(self, xml_data):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| xml_data | **bytes** | XML data nové části, která má být přidána. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData je `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData je prázdný nebo neplatný. |


## add(self, xml_string) {#str}
Přidá novou vlastní část XML.

### Návratová hodnota

Vytvořená vlastní část XML.



```python
def add(self, xml_string):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| xml_string | **str** | XML řetězec nové části, která má být přidána. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString je `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString je prázdný nebo xml-data je neplatná. |


## add(self, input_stream) {#iorawiobase}
Přidá novou vlastní část XML.

### Návratová hodnota

Vytvořená vlastní část XML.



```python
def add(self, input_stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Vstupní proud s XML daty nové části, která má být přidána. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream je `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Data v inputStream jsou prázdná nebo Sinvalid. |



### Viz také
* třída [`ICustomXmlPart`](/slides/python-net/cs/aspose.slides/icustomxmlpart)
* třída [`ICustomXmlPartCollection`](/slides/python-net/cs/aspose.slides/icustomxmlpartcollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)