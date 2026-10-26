---
title: check_write_protection method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Avgör om en presentation är lösenordsskyddad för att modifieras.

### Returnerar

Sant om lösenordet är giltigt; annars falskt.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | **str** | Lösenordet för att kontrollera. |

### Anmärkningar

1. Du bör kontrollera egenskapen [`ProtectionManager.is_write_protected`](/slides/python-net/sv/aspose.slides/protectionmanager/is_write_protected) innan du anropar den här metoden.
2. När lösenordet är None eller tomt, returnerar den här metoden falskt.



### Se även
* klass [`ProtectionManager`](/slides/python-net/sv/aspose.slides/protectionmanager)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)