---
title: LINQ_Select()
second_title: Aspose.Slides C++ API-referencia
description: Átalakítja egy sorozat elemeit.
type: docs
weight: 248
url: /hu/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) metódus


Átalakítja egy sorozat elemeit.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| ResultType | A **selector** által visszaadott érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Átalakító függvény. |

### Visszatérési érték

[IEnumerable](../) objektum, amely a **selector** függvény által visszaadott elemeket tartalmazza.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) metódus


Átalakítja a sorozat minden elemét új formába, az elem indexének beépítésével.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| ResultType | A **selector** által visszaadott érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | Átalakító függvény. |

### Visszatérési érték

[IEnumerable](../) objektum, amely a **selector** függvény által visszaadott elemeket tartalmazza.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) metódus




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) metódus




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IEnumerable](../)
* Osztály [Func](../../../system/func/)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)