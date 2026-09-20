---
title: check_write_protection method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Kontroluje, zda je heslo pro úpravu správné u prezentace chráněné před zápisem.

### Návratová hodnota
True pokud je prezentace chráněna před zápisem a heslo je správné. False jinak.



```python
def check_write_protection(self, password):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| password | **str** | Heslo, které se má zkontrolovat. |

### Poznámky
1. Měli byste zkontrolovat vlastnost [`PresentationInfo.is_write_protected`](/slides/python-net/cs/aspose.slides/presentationinfo/is_write_protected) před voláním této metody.
2. Když je heslo None nebo prázdné, tato metoda vrací false.

### Výjimky
| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Viz také
* třída [`PresentationInfo`](/slides/python-net/cs/aspose.slides/presentationinfo)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)