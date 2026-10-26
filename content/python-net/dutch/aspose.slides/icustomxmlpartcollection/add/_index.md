---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
Voegt een nieuw aangepast xml-gedeelte toe.

### Retourneert

Aangemaakt aangepast xml-gedeelte.



```python
def add(self, xml_data):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| xml_data | **bytes** | De xml-gegevens van het nieuwe onderdeel dat moet worden toegevoegd. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData is `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData is leeg of ongeldig. |


## add(self, xml_string) {#str}
Voegt een nieuw aangepast xml-gedeelte toe.

### Retourneert

Aangemaakt aangepast xml-gedeelte.



```python
def add(self, xml_string):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| xml_string | **str** | De xml-string van het nieuwe onderdeel dat moet worden toegevoegd. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString is `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString is leeg of xml-data is ongeldig. |


## add(self, input_stream) {#iorawiobase}
Voegt een nieuw aangepast xml-gedeelte toe.

### Retourneert

Aangemaakt aangepast xml-gedeelte.



```python
def add(self, input_stream):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | De inputStream met xml-gegevens van het nieuwe onderdeel dat moet worden toegevoegd. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream is `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Data in inputStream is leeg of Sinvalid. |



### Zie ook
* klasse [`ICustomXmlPart`](/slides/python-net/nl/aspose.slides/icustomxmlpart)
* klasse [`ICustomXmlPartCollection`](/slides/python-net/nl/aspose.slides/icustomxmlpartcollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)