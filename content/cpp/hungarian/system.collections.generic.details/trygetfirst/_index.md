---
title: TryGetFirst()
second_title: Aspose.Slides for C++ API referenciája
description: Megpróbálja lekérni a gyűjtemény első elemét.
type: docs
weight: 248
url: /hu/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) function


Megpróbálja lekérni a gyűjtemény első elemét.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | A gyűjtemény elemeinek típusa. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | A gyűjtemény, amelyből egy elemet kell megszerezni. |
| found | **bool**\& | A kimeneti paraméter. Igaz értéket ad vissza, ha a gyűjtemény tartalmaz bármely elemet. Különben hamis érték visszatér. |

### Return Value

Visszaadja a gyűjtemény első elemét. Ha a gyűjtemény üres, a típus alapértelmezett értéke lesz visszaadva.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) function


Megpróbálja lekérni a gyűjtemény első olyan elemét, amely megfelel a predikátum függvénynek.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | A gyűjtemény elemeinek típusa. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | A gyűjtemény, amelyből egy elemet kell megszerezni. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | A predikátum függvény. |
| found | **bool**\& | A kimeneti paraméter. Igaz értéket ad vissza, ha a gyűjtemény tartalmaz bármely elemet. Különben hamis érték visszatér. |

### Return Value

Visszaadja a gyűjtemény első elemét. Ha nem található a megadott predikátum függvénynek megfelelő elem, a típus alapértelmezett értéke lesz visszaadva.

## Lásd még

* Osztály [IEnumerable](../../system.collections.generic/ienumerable/)
* Osztály [Func](../../system/func/)
* Névtér [System::Collections::Generic::Details](../)
* Könyvtár [Aspose.Slides](../../)