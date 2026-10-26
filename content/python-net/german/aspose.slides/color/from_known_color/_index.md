---
title: from_known_color method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Erstellt eine Farbe aus der angegebenen vordefinierten Farbe.<br/>Dies ist der einzige Weg, um eine Systemfarbe zu erhalten (z. B. `KnownColor.CONTROL`): Systemfarben werden nicht als `Color`-Attribute bereitgestellt, weil ihre Werte vom Desktophintergrund abhängen, sodass sie zur Laufzeit aus der Bibliothek gelesen werden.

### Rückgabewert

Die Farbe, die diese Methode erstellt.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| known_color | **KnownColor** | Ein Element der `KnownColor`-Aufzählung (ein `IntEnum`, das .NET `System.Drawing.KnownColor` spiegelt) oder sein ganzzahliger Wert. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **ValueError** | Der Wert ist kein gültiges `KnownColor`-Element. |



### Siehe auch
* Klasse [`Color`](/slides/python-net/de/aspose.slides/color)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)