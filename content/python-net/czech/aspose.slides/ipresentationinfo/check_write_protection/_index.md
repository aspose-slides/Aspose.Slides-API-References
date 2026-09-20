---
title: check_write_protection method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Kontroluje, zda je heslo pro úpravu správné pro prezentaci chráněnou proti zápisu.

### Returns
Návratová hodnota

True, pokud je prezentace chráněna proti zápisu a heslo je správné. False jinak.



```python
def check_write_protection(self, password):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| password | **str** | Heslo, které se má zkontrolovat. |

### Remarks
Poznámky

1. Měli byste zkontrolovat vlastnost [`IPresentationInfo.is_write_protected`](/slides/python-net/cs/aspose.slides/ipresentationinfo/is_write_protected) před voláním této metody.
2. Když je heslo None nebo prázdné, tato metoda vrací false.

### Exceptions
Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### See Also
* třída [`IPresentationInfo`](/slides/python-net/cs/aspose.slides/ipresentationinfo)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)