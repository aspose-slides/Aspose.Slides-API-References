---
title: MakeYieldEnumerable()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy IEnumerable-t egy yield függvényből.
type: docs
weight: 2419
url: /hu/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) function

Létrehoz egy IEnumerable-t egy yield függvényből.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A sorozat elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | A végrehajtandó yield függvény |

### Visszatérési érték

Megosztott mutató az IEnumerable-re

## Lásd még

* Typedef [SharedPtr](../sharedptr/)
* Osztály [IEnumerable](../../system.collections.generic/ienumerable/)
* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)