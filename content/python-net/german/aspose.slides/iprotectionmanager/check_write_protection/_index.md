---
title: check_write_protection method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Bestimmt, ob eine Präsentation passwortgeschützt ist, um sie zu ändern.

### Rückgabewert

True if the password is valid; otherwise, false.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| password | **str** | Das Passwort für die Überprüfung. |

### Bemerkungen

1. Sie sollten die [`IProtectionManager.is_write_protected`](/slides/python-net/de/aspose.slides/iprotectionmanager/is_write_protected) Eigenschaft prüfen, bevor Sie diese Methode aufrufen.
2. Wenn das Passwort None oder leer ist, gibt diese Methode false zurück.



### Siehe auch
* Klasse [`IProtectionManager`](/slides/python-net/de/aspose.slides/iprotectionmanager)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)