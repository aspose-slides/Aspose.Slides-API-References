---
title: check_password method
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Sprawdza, czy podane hasło jest poprawne dla prezentacji zabezpieczonej otwartym hasłem.

### Zwraca

True jeśli prezentacja jest zabezpieczona otwartym hasłem i podane hasło jest prawidłowe, w przeciwnym razie false.



```python
def check_password(self, password):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| password | **str** | Hasło do sprawdzenia. |

### Uwagi

Gdy hasło jest None lub puste, ta metoda zwraca false.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### Zobacz także
* klasa [`PresentationInfo`](/slides/python-net/pl/aspose.slides/presentationinfo)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)