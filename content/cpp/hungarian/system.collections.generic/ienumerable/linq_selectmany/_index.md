---
title: LINQ_SelectMany()
second_title: Aspose.Slides C++ API referencia
description: A sorozat minden elemét projektálja, és a keletkezett sorozatokat egyetlen sorozatba egyesíti.
type: docs
weight: 300
url: /hu/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) metódus


Projekti minden egyes elemét egy sorozatnak, és a keletkező sorozatokat egyetlen sorozatba egyesíti.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| ResultType | A **selector** által visszaadott érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Átalakító függvény. |

### Visszatérési érték

Egy [IEnumerable](../), amely a bemeneti sorozat minden elemére egy-több-re vetítő függvény meghívásának eredményét tartalmazza.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) metódus




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IEnumerable](../)
* Osztály [Func](../../../system/func/)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)