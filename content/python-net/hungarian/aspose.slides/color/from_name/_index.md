---
title: from_name method
second_title: Aspose.Slides for Python a .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Létrehozza a színt a megadott előre definiált szín nevéből.<br/>A keresés nem különbözteti meg a nagy- és kisbetűket, és figyelmen kívül hagyja az aláhúzásokat és a szóközöket: `"LightBlue"`, `"lightblue"` és `"light_blue"` mind a `Color.light_blue`-ra mutat. Lásd a [`Color`](/slides/python-net/hu/aspose.slides/color) osztály oldalát az előre definiált színek listájáért.

### Visszatérési érték

A név szerinti szín.



```python
@staticmethod
def from_name(name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| name | **str** | Egy karakterlánc, amely egy előre definiált szín neve. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **ValueError** | A név nem egy előre definiált szín neve. |
| **TypeError** | A név nem karakterlánc. |



### Lásd még
* osztály [`Color`](/slides/python-net/hu/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)