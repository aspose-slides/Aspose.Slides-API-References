---
title: LINQ_Max()
second_title: Aspose.Slides C++ API referenciája
description: Minden egyes elemre meghív egy transzformáló függvényt egy általános sorozatban, és visszaadja a legnagyobb eredményértéket.
type: docs
weight: 352
url: /hu/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) metódus


Minden egyes elemre meghív egy transzformáló függvényt egy általános sorozatban, és visszaadja a legnagyobb eredményértéket.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| ResultType | A selector által visszaadott érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Minden elemre alkalmazandó transzformáló függvény. |

### Visszatérési érték

A sorozat legnagyobb értéke.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) metódus




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Lásd még

* Osztály [Func](../../../system/func/)
* Osztály [IEnumerable](../)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)