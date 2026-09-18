---
title: check_write_protection method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Megállapítja, hogy a bemutató jelszóval védett-e a módosításra.

### Visszatérési érték

True, ha a jelszó érvényes; egyébként false.



```python
def check_write_protection(self, password):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| password | **str** | A jelszó a ellenőrzéshez. |

### Megjegyzések

1. A módszer hívása előtt ellenőrizni kell a [`ProtectionManager.is_write_protected`](/slides/python-net/hu/aspose.slides/protectionmanager/is_write_protected) tulajdonságot.
2. Ha a jelszó None vagy üres, ez a metódus false értéket ad vissza.



### Lásd még
* osztály [`ProtectionManager`](/slides/python-net/hu/aspose.slides/protectionmanager)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)