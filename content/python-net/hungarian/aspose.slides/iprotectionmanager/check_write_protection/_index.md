---
title: check_write_protection method
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Megállapítja, hogy a bemutató jelszóval védett-e a módosításra.

### Visszatérési érték

Igaz, ha a jelszó érvényes; egyébként hamis.



```python
def check_write_protection(self, password):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| password | **str** | A jelszó ellenőrzéshez. |

### Megjegyzések

1. Ellenőriznie kell a [`IProtectionManager.is_write_protected`](/slides/python-net/hu/aspose.slides/iprotectionmanager/is_write_protected) tulajdonságot, mielőtt meghívja ezt a metódust.
2. Ha a jelszó None vagy üres, ez a metódus hamis értéket ad vissza.



### Lásd még
* osztály [`IProtectionManager`](/slides/python-net/hu/aspose.slides/iprotectionmanager)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)