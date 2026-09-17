---
title: check_write_protection method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Überprüft, ob ein zum Ändern verwendetes Passwort für eine schreibgeschützte Präsentation korrekt ist.

### Returns

True, wenn die Präsentation schreibgeschützt ist und das Passwort korrekt ist. Andernfalls False.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| password | **str** | Das zu prüfende Passwort. |

### Hinweise
1. Sie sollten die [`PresentationInfo.is_write_protected`](/slides/python-net/de/aspose.slides/presentationinfo/is_write_protected)-Eigenschaft überprüfen, bevor Sie diese Methode aufrufen.
2. Wenn das Passwort None oder leer ist, gibt diese Methode false zurück.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |

### Siehe auch
* Klasse [`PresentationInfo`](/slides/python-net/de/aspose.slides/presentationinfo)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)