---
title: check_write_protection method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/presentationinfo/check_write_protection/
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
| password | **str** | Lösenordet som ska kontrolleras. |

### Anmärkningar

1. Du bör kontrollera [`PresentationInfo.is_write_protected`](/slides/python-net/sv/aspose.slides/presentationinfo/is_write_protected)-egenskapen innan du anropar den här metoden.
2. När lösenordet är None eller tomt, returnerar den här metoden falskt.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Se även
* klass [`PresentationInfo`](/slides/python-net/sv/aspose.slides/presentationinfo)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)