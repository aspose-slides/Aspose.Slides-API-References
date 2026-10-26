---
title: add method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

### Rückgabe

Benutzerdefinierter XML-Teil erstellt.



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


## add(self, xml_string) {#str}
Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

### Rückgabe

Benutzerdefinierter XML-Teil erstellt.



```python
def add(self, xml_string):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| xml_string | **str** | Die XML-Zeichenkette des neuen Teils, der hinzugefügt werden soll. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString ist `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString ist leer oder xml-data ist ungültig. |


## add(self, input_stream) {#iorawiobase}
Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

### Rückgabe

Benutzerdefinierter XML-Teil erstellt.



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
* Klasse [`ICustomXmlPart`](/slides/python-net/de/aspose.slides/icustomxmlpart)
* Klasse [`ICustomXmlPartCollection`](/slides/python-net/de/aspose.slides/icustomxmlpartcollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)