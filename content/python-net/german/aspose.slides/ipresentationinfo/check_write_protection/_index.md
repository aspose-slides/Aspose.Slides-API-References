---
title: check_write_protection method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Überprüft, ob ein Passwort zum Ändern für eine schreibgeschützte Präsentation korrekt ist.

### Rückgabewert
True, wenn die Präsentation schreibgeschützt ist und das Passwort korrekt ist. False andernfalls.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| password | **str** | Das zu überprüfende Passwort. |

### Hinweise
1. Sie sollten die [`IPresentationInfo.is_write_protected`](/slides/python-net/de/aspose.slides/ipresentationinfo/is_write_protected)-Eigenschaft prüfen, bevor Sie diese Methode aufrufen.
2. Wenn das Passwort None oder leer ist, gibt diese Methode false zurück.

### Ausnahmen

| Exception | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Siehe auch
* class [`IPresentationInfo`](/slides/python-net/de/aspose.slides/ipresentationinfo)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)