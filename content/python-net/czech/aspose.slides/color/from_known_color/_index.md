---
title: from_known_color method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Vytvoří barvu ze zadané předdefinované barvy.<br/>Toto je jediný způsob, jak získat systémovou barvu (například `KnownColor.CONTROL`): systémové barvy nejsou vystaveny jako atributy `Color`, protože jejich hodnoty závisí na motivu pracovního prostředí, a proto jsou načítány z runtime knihovny.

### Návratová hodnota

Barva, kterou tato metoda vytvoří.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| known_color | **KnownColor** | Prvek výčtu `KnownColor` ( `IntEnum` odrážející .NET `System.Drawing.KnownColor`) nebo jeho celočíselná hodnota. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **ValueError** | Hodnota není platným členem `KnownColor`. |



### Viz také
* třída [`Color`](/slides/python-net/cs/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)