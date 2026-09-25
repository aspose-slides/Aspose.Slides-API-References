---
title: from_known_color method
second_title: Aspose.Slides dla Pythona poprzez .NET API
description: 
type: docs
url: /pl/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Tworzy kolor z określonego wstępnie zdefiniowanego koloru.<br/>To jedyny sposób uzyskania koloru systemowego (takiego jak `KnownColor.CONTROL`): kolory systemowe nie są udostępniane jako atrybuty `Color`, ponieważ ich wartości zależą od motywu pulpitu, więc są odczytywane z środowiska uruchomieniowego biblioteki.

### Zwraca

Kolor tworzony przez tę metodę.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| known_color | **KnownColor** | Element wyliczenia `KnownColor` (`IntEnum` odzwierciedlający .NET `System.Drawing.KnownColor`) lub jego wartość całkowitą. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **ValueError** | Wartość nie jest prawidłowym członkiem `KnownColor`. |



### Zobacz także
* klasa [`Color`](/slides/python-net/pl/aspose.slides/color)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)