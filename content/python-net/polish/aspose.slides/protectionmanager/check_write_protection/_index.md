---
title: check_write_protection method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Określa, czy prezentacja jest chroniona hasłem przed modyfikacją.

### Zwraca

True jeśli hasło jest prawidłowe; w przeciwnym razie false.



```python
def check_write_protection(self, password):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| password | **str** | Hasło do sprawdzenia. |

### Uwagi

1. Powinieneś sprawdzić właściwość [`ProtectionManager.is_write_protected`](/slides/python-net/pl/aspose.slides/protectionmanager/is_write_protected) przed wywołaniem tej metody.
2. Gdy hasło jest None lub puste, ta metoda zwraca false.



### Zobacz również
* klasa [`ProtectionManager`](/slides/python-net/pl/aspose.slides/protectionmanager)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)