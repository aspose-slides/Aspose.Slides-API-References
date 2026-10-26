---
title: check_password method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Kontrollerar om ett lösenord är korrekt för en presentation som är skyddad med öppet lösenord.

### Returnerar

Sant om presentationen är skyddad med öppet lösenord och lösenordet är korrekt, annars falskt.



```python
def check_password(self, password):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | **str** | Lösenordet att kontrollera. |

### Anmärkningar

När lösenordet är None eller tomt, returnerar den här metoden falskt.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### Se även
* klass [`PresentationInfo`](/slides/python-net/sv/aspose.slides/presentationinfo)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)