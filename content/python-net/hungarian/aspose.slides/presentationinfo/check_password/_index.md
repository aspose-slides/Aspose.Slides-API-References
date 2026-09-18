---
title: check_password method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Ellenőrzi, hogy a nyílt jelszóval védett prezentáció esetén a jelszó helyes-e.

### Returns
True, ha a prezentáció nyílt jelszóval védett és a jelszó helyes, egyébként false.



```python
def check_password(self, password):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| password | **str** | A ellenőrzendő jelszó. |

### Remarks
Ha a jelszó None vagy üres, ez a metódus false értéket ad vissza.

### Exceptions

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### See Also
* osztály [`PresentationInfo`](/slides/python-net/hu/aspose.slides/presentationinfo)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)