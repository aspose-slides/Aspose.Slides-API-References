---
title: from_known_color method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Skapar en färg från den angivna fördefinierade färgen.<br/>Detta är det enda sättet att erhålla en systemfärg (t.ex. `KnownColor.CONTROL`): systemfärger exponeras inte som `Color`-attribut eftersom deras värden beror på skrivbordstemat, så de läses från bibliotekets körtid.

### Returnerar

Den färg som den här metoden skapar.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| known_color | **KnownColor** | Ett element i `KnownColor`-enumerationen (en `IntEnum` som speglar .NET `System.Drawing.KnownColor`) eller dess heltalsvärde. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **ValueError** | Värdet är inte en giltig `KnownColor`-medlem. |



### Se även
* klass [`Color`](/slides/python-net/sv/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)