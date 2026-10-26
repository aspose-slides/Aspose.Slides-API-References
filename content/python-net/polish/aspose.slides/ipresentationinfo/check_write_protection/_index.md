---
title: check_write_protection method
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Sprawdza, czy hasło do modyfikacji jest prawidłowe dla prezentacji zabezpieczonej przed zapisem.

### Zwraca

True jeśli prezentacja jest zabezpieczona przed zapisem i hasło jest prawidłowe. False w przeciwnym razie.



```python
def check_write_protection(self, password):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| password | **str** | Hasło do sprawdzenia. |

### Uwagi

1. Powinieneś sprawdzić właściwość [`IPresentationInfo.is_write_protected`](/slides/python-net/pl/aspose.slides/ipresentationinfo/is_write_protected) przed wywołaniem tej metody.
2. Gdy hasło jest None lub puste, ta metoda zwraca false.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Zobacz także
* klasa [`IPresentationInfo`](/slides/python-net/pl/aspose.slides/ipresentationinfo)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)