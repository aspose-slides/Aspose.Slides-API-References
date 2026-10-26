---
title: LINQ_Average()
second_title: Aspose.Slides C++ API-referencia
description: Kiszámítja a numerikus értékek sorozatának átlagát.
type: docs
weight: 365
url: /hu/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() metódus

Kiszámítja egy numerikus értékek sorozatának átlagát.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```

### Visszatérési érték

Az értékek sorozatának átlaga.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) metódus

Kiszámítja egy értékek sorozatának átlagát, amelyet egy átalakító függvény meghívásával kapunk a bemeneti sorozat minden elemére.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| ResultType | A selector által visszaadott érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Az a transform funkció, amelyet minden elemre alkalmazunk. |

### Visszatérési érték

A leképzett értékek átlaga.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) metódus

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Lásd még

* Osztály [IEnumerable](../)
* Osztály [Func](../../../system/func/)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)