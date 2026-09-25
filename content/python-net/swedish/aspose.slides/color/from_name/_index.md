---
title: from_name method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Skapar en färg från det angivna namnet på en fördefinierad färg.<br/>Uppslagningen är skiftlägesokänslig och ignorerar understrykningar och mellanslag: `"LightBlue"`, `"lightblue"` och `"light_blue"` alla mappar till `Color.light_blue`. Se [`Color`](/slides/python-net/sv/aspose.slides/color) klasssida för listan över fördefinierade färger.

### Returnerar

Den namngivna färgen.



```python
@staticmethod
def from_name(name):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | **str** | En sträng som är namnet på en fördefinierad färg. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **ValueError** | Namnet är inte ett namn på en fördefinierad färg. |
| **TypeError** | Namnet är inte en sträng. |



### Se även
* klass [`Color`](/slides/python-net/sv/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)