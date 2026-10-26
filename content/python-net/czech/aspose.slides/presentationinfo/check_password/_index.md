---
title: check_password method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Kontroluje, zda je heslo správné pro prezentaci chráněnou otevřeným heslem.

### Návratová hodnota

True, pokud je prezentace chráněna otevřeným heslem a heslo je správné, a false jinak.



```python
def check_password(self, password):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| password | **str** | Heslo, které se má zkontrolovat. |

### Poznámky

Když je heslo None nebo prázdné, tato metoda vrací false.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### Viz také
* třída [`PresentationInfo`](/slides/python-net/cs/aspose.slides/presentationinfo)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)