---
title: check_write_protection method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Bestimmt, ob eine Präsentation passwortgeschützt ist, um sie zu ändern.

### Returns
True if the password is valid; otherwise, false.

```python
def check_write_protection(self, password):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| password | **str** | Das Passwort zum Überprüfen. |

### Remarks
1. Sie sollten die [`ProtectionManager.is_write_protected`](/slides/python-net/de/aspose.slides/protectionmanager/is_write_protected)-Eigenschaft prüfen, bevor Sie diese Methode aufrufen.
2. Wenn das Passwort None oder leer ist, gibt diese Methode false zurück.

### See Also
* Klasse [`ProtectionManager`](/slides/python-net/de/aspose.slides/protectionmanager)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)