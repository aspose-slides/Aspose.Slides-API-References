---
title: check_write_protection method
second_title: Aspose.Slides Pythonhoz a .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Ellenőrzi, hogy a módosításhoz szükséges jelszó helyes-e egy írásvédett bemutató esetén.

### Visszatérési érték

True, ha a bemutató írásvédett és a jelszó helyes. False ellenkező esetben.

```python
def check_write_protection(self, password):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| password | **str** | A ellenőrzendő jelszó. |

### Megjegyzések

1. Ellenőriznie kell a [`PresentationInfo.is_write_protected`](/slides/python-net/hu/aspose.slides/presentationinfo/is_write_protected) tulajdonságot, mielőtt meghívja ezt a metódust.
2. Ha a jelszó None vagy üres, ez a metódus false értéket ad vissza.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |

### Lásd még
* osztály [`PresentationInfo`](/slides/python-net/hu/aspose.slides/presentationinfo)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)