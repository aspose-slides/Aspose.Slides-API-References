---
title: from_name method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Erstellt eine Farbe aus dem angegebenen Namen einer vordefinierten Farbe.<br/>Die Suche ist nicht case-sensitiv und ignoriert Unterstriche und Leerzeichen: `"LightBlue"`, `"lightblue"` und `"light_blue"` lösen alle zu `Color.light_blue`. Siehe die [`Color`](/slides/python-net/de/aspose.slides/color) Klassen-Seite für die Liste der vordefinierten Farben.

### Rückgabe

Die benannte Farbe.



```python
@staticmethod
def from_name(name):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | **str** | Ein String, der der Name einer vordefinierten Farbe ist. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **ValueError** | Der Name ist kein Name einer vordefinierten Farbe. |
| **TypeError** | Der Name ist kein String. |



### Siehe auch
* Klasse [`Color`](/slides/python-net/de/aspose.slides/color)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)