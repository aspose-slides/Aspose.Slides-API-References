---
title: TryGetLast()
second_title: Aspose.Slides for C++ API-referencia
description: Megpróbálja lekérni a gyűjtemény utolsó elemét.
type: docs
weight: 261
url: /hu/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) függvény


Megpróbálja lekérni a gyűjtemény utolsó elemét.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A gyűjtemény elemeinek típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | A gyűjtemény, amelyből egy elemet kell szerezni. |
| found | **bool**\& | A kimeneti paraméter. Igaz értéket ad vissza, ha a gyűjtemény tartalmaz bármilyen elemet. Ellenkező esetben hamis értéket ad vissza. |

### Visszatérési érték

Visszaadja a gyűjtemény utolsó elemét. A típus alapértelmezett értéke lesz visszaadva, ha a gyűjtemény üres.

## Lásd még

* Osztály [IEnumerable](../../system.collections.generic/ienumerable/)
* Névtér [System::Collections::Generic::Details](../)
* Könyvtár [Aspose.Slides](../../)