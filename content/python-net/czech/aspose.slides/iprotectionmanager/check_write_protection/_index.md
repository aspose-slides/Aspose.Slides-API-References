---
title: check_write_protection method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Určuje, zda je prezentace chráněna heslem proti úpravám.

### Vrací
True, pokud je heslo platné; jinak false.

```python
def check_write_protection(self, password):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| password | **str** | Heslo pro kontrolu. |

### Poznámky
1. Měli byste zkontrolovat vlastnost [`IProtectionManager.is_write_protected`](/slides/python-net/cs/aspose.slides/iprotectionmanager/is_write_protected) před voláním této metody.
2. Když je heslo None nebo prázdné, tato metoda vrací false.

### Viz také
* třída [`IProtectionManager`](/slides/python-net/cs/aspose.slides/iprotectionmanager)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)