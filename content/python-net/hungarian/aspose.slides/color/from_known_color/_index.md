---
title: from_known_color method
second_title: Aspose.Slides for Python a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Létrehoz egy színt a megadott előre definiált színből.<br/>Ez az egyetlen módja annak, hogy rendszer színt szerezzünk (például `KnownColor.CONTROL`): a rendszer színeket nem teszik közzé `Color` attribútumként, mivel azok értékei az asztali témától függenek, ezért a könyvtár futási környezetéből olvasódnak be.

### Visszatérési érték

A szín, amelyet ez a metódus létrehoz.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| known_color | **KnownColor** | A `KnownColor` felsorolt típusa egy eleme (egy `IntEnum`, amely tükrözi a .NET `System.Drawing.KnownColor` értékét) vagy annak egész értéke. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **ValueError** | Az érték nem érvényes `KnownColor` elem. |



### Lásd még
* osztály [`Color`](/slides/python-net/hu/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)