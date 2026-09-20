---
title: check_write_protection method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Kontrollerar om ett lösenord för att ändra är korrekt för en skrivskyddad presentation.

### Returnerar

Sant om presentationen är skrivskyddad och lösenordet är korrekt. Falskt annars.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | **str** | Lösenordet att kontrollera. |

### Anmärkningar

1. Du bör kontrollera egenskapen [`IPresentationInfo.is_write_protected`](/slides/python-net/sv/aspose.slides/ipresentationinfo/is_write_protected) innan du anropar den här metoden.
2. När lösenordet är None eller tomt, returnerar den här metoden falskt.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Se även
* klass [`IPresentationInfo`](/slides/python-net/sv/aspose.slides/ipresentationinfo)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)