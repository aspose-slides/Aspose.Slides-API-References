---
title: from_argb method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Erstellt eine Farbe aus einem 32-bit-ARGB-Wert.

### Rückgabewert

Die aus dem angegebenen Wert erstellte Farbe.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb | **int** | A value specifying the 32-bit ARGB value (signed or unsigned). |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |


## from_argb(alpha, base_color) {#int-color}
Erstellt eine Farbe aus dem angegebenen Alpha-Wert und der Basisfarbe.

### Rückgabewert

Die aus den angegebenen Werten erstellte Farbe.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| alpha | **int** | Der Alpha-Komponentenwert. Gültige Werte liegen zwischen 0 und 255. |
| base_color | [`Color`](/slides/python-net/de/aspose.slides/color) | Die Farbe, aus der die neue Farbe erstellt wird. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |


## from_argb(red, green, blue) {#int-int-int}
Erstellt eine undurchsichtige Farbe (Alpha ist 255) aus den angegebenen Rot-, Grün- und Blauwerten.

### Rückgabewert

Die aus den angegebenen Werten erstellte Farbe.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| red | **int** | The red component value. Valid values are 0 through 255. |
| green | **int** | The green component value. Valid values are 0 through 255. |
| blue | **int** | The blue component value. Valid values are 0 through 255. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Erstellt eine Farbe aus den vier ARGB-Komponenten (Alpha, Rot, Grün und Blau).

### Rückgabewert

Die aus den angegebenen Werten erstellte Farbe.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| alpha | **int** | The alpha component value. Valid values are 0 through 255. |
| red | **int** | The red component value. Valid values are 0 through 255. |
| green | **int** | The green component value. Valid values are 0 through 255. |
| blue | **int** | The blue component value. Valid values are 0 through 255. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **ValueError** | A component value is less than 0 or greater than 255. |
| **TypeError** | Wrong number or type of arguments. |



### Siehe auch
* Klasse [`Color`](/slides/python-net/de/aspose.slides/color)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)