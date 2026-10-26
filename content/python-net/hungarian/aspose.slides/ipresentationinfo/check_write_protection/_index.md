---
title: check_write_protection method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Ellenőrzi, hogy a módosításhoz szükséges jelszó helyes-e egy írásvédett prezentáció esetén.

### Visszatérési érték

True, ha a prezentáció írásvédett és a jelszó helyes. Egyébként False.

```python
def check_write_protection(self, password):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| password | **str** | Az ellenőrzendő jelszó. |

### Megjegyzések

1. Ellenőriznie kell a [`IPresentationInfo.is_write_protected`](/slides/python-net/hu/aspose.slides/ipresentationinfo/is_write_protected) tulajdonságot, mielőtt meghívja ezt a metódust.
2. Ha a jelszó None vagy üres, ez a metódus false-t ad vissza.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |

### Lásd még
* osztály [`IPresentationInfo`](/slides/python-net/hu/aspose.slides/ipresentationinfo)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)