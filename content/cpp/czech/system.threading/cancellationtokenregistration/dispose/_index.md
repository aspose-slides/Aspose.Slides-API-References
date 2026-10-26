---
title: Dispose()
second_title: Aspose.Slides pro C++ API Reference
description: Zruší registraci a odstraní callback z přidruženého CancellationTokenSource. Po zavolání této metody již nebude registrovaný callback vyvolán, když je přidružený CancellationTokenSource zrušen.
type: docs
weight: 1
url: /cs/system.threading/cancellationtokenregistration/dispose/
---
## CancellationTokenRegistration::Dispose() metoda

Zruší registraci a odstraní zpětnou funkci z přidruženého [CancellationTokenSource](../../cancellationtokensource/). Po zavolání této metody nebude registrované zpětné volání dále vyvoláno, když je přidružený [CancellationTokenSource](../../cancellationtokensource/) zrušen.

```cpp
void System::Threading::CancellationTokenRegistration::Dispose()
```

## Poznámky

Je bezpečné volat tuto metodu vícekrát - následné volání nebude mít žádný vliv.

## Viz také

* Třída [CancellationTokenRegistration](../)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)