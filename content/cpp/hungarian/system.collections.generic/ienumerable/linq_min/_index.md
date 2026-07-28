---
title: LINQ_Min()
second_title: Aspose.Slides C++ API-referencia
description: Átalakító függvényt hív meg a generikus sorozat minden elemére, és visszaadja a legkisebb eredményértéket.
type: docs
weight: 339
url: /hu/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) method


Átalakító függvényt hív meg a generikus sorozat minden elemére, és visszaadja a legkisebb eredményértéket.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| ResultType | A selector által visszaadott érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Egy átalakító függvény, amelyet minden elemre alkalmaznak. |

### Visszatérési érték

A sorozat legkisebb értéke.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Lásd még

* Osztály [Func](../../../system/func/)
* Osztály [IEnumerable](../)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)