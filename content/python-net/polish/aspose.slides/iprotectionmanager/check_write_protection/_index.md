---
title: check_write_protection method
second_title: Aspose.Slides dla Pythona przez .NET API – Referencja
description: 
type: docs
url: /pl/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Określa, czy prezentacja jest chroniona hasłem przed modyfikacją.

### Zwraca
True, jeśli hasło jest prawidłowe; w przeciwnym razie false.



```python
def check_write_protection(self, password):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| password | **str** | Hasło do sprawdzenia. |

### Uwagi
1. Należy sprawdzić właściwość [`IProtectionManager.is_write_protected`](/slides/python-net/pl/aspose.slides/iprotectionmanager/is_write_protected) przed wywołaniem tej metody.
            2. Gdy hasło jest None lub puste, metoda zwraca false.

### Zobacz także
* klasa [`IProtectionManager`](/slides/python-net/pl/aspose.slides/iprotectionmanager)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)