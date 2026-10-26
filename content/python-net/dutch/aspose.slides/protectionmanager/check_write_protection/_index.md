---
title: check_write_protection method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Bepaalt of een presentatie met een wachtwoord is beveiligd om te wijzigen.

### Retour
True als het wachtwoord geldig is; anders false.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| password | **str** | Het wachtwoord voor controle. |

### Opmerkingen

1. U moet de eigenschap [`ProtectionManager.is_write_protected`](/slides/python-net/nl/aspose.slides/protectionmanager/is_write_protected) controleren voordat u deze methode aanroept.
2. Wanneer het wachtwoord None of leeg is, retourneert deze methode false.



### Zie ook
* klasse [`ProtectionManager`](/slides/python-net/nl/aspose.slides/protectionmanager)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)