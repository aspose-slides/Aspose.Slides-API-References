---
title: MakeYieldEnumerator()
second_title: Aspose.Slides for C++ API referenciája
description: Létrehoz egy IEnumerator-t egy yield függvényből.
type: docs
weight: 2432
url: /hu/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) függvény

Létrehoz egy IEnumerator-t egy yield függvényből.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A sorozat elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | A végrehajtandó yield függvény |

### Visszatérési érték

Megosztott mutató az IEnumerator-re

## Lásd még

* Típusdefiníció [SharedPtr](../sharedptr/)
* Osztály [IEnumerator](../../system.collections.generic/ienumerator/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)