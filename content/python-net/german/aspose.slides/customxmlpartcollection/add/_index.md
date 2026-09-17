---
title: add method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
Fügt ein neues benutzerdefiniertes XML-Teil hinzu.

### Rückgabe

Erstelltes benutzerdefiniertes XML-Teil.



```python
def add(self, xml_string):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| xml_string | **str** | Der XML-String des neuen Teils, der hinzugefügt werden soll. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString ist `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString ist leer oder XML-Daten sind ungültig. |


## add(self, xml_data) {#bytes}
Fügt ein neues benutzerdefiniertes XML-Teil hinzu.

### Rückgabe

Erstelltes benutzerdefiniertes XML-Teil.



```python
def add(self, xml_data):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| xml_data | **bytes** | Die XML-Daten des neuen Teils, der hinzugefügt werden soll. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData ist `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData ist leer oder ungültig. |


## add(self, input_stream) {#iorawiobase}
Fügt ein neues benutzerdefiniertes XML-Teil hinzu.

### Rückgabe

Erstelltes benutzerdefiniertes XML-Teil.



```python
def add(self, input_stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Der inputStream mit XML-Daten des neuen Teils, der hinzugefügt werden soll. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream ist `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Daten im inputStream sind leer oder ungültig. |



### Siehe auch
* Klasse [`CustomXmlPartCollection`](/slides/python-net/de/aspose.slides/customxmlpartcollection)
* Klasse [`ICustomXmlPart`](/slides/python-net/de/aspose.slides/icustomxmlpart)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)