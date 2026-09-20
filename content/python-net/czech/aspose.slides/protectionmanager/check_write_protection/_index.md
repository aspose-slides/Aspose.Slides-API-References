---
title: check_write_protection method
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Určuje, zda je prezentace chráněna heslem proti úpravám.

### Návratová hodnota

True, pokud je heslo platné; jinak false.



```python
def check_write_protection(self, password):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| password | **str** | Heslo pro kontrolu. |

### Poznámky

1. Před voláním této metody byste měli zkontrolovat vlastnost [`ProtectionManager.is_write_protected`](/slides/python-net/cs/aspose.slides/protectionmanager/is_write_protected).
2. Když je heslo None nebo prázdné, tato metoda vrátí false.



### Viz také
* třída [`ProtectionManager`](/slides/python-net/cs/aspose.slides/protectionmanager)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)