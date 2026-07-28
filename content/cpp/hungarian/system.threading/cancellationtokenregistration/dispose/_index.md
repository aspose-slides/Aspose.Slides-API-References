---
title: Dispose()
second_title: Aspose.Slides for C++ API referenciája
description: Megszünteti a regisztrációt, és eltávolítja a visszahívást a kapcsolt CancellationTokenSource-ból. A metódus meghívása után a regisztrált visszahívás már nem lesz meghívva, ha a kapcsolt CancellationTokenSource visszavonásra kerül.
type: docs
weight: 1
url: /hu/system.threading/cancellationtokenregistration/dispose/
---
## CancellationTokenRegistration::Dispose() metódus

Megszünteti a regisztrációt, és eltávolítja a visszahívást a kapcsolt [CancellationTokenSource](../../cancellationtokensource/)-ből. A metódus meghívása után a regisztrált visszahívás már nem lesz meghívva, ha a kapcsolt [CancellationTokenSource](../../cancellationtokensource/) visszavonásra kerül.

```cpp
void System::Threading::CancellationTokenRegistration::Dispose()
```

## Megjegyzés

Biztonságos, ha ezt a metódust többször meghívják - a későbbi hívások nem lesznek hatással.

## Lásd még

* Osztály [CancellationTokenRegistration](../)
* Névterület [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)