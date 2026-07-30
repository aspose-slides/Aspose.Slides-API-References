---
title: LINQ_Average()
second_title: Aspose.Slides pro C++ API Reference
description: Vypočítá průměr sekvence číselných hodnot.
type: docs
weight: 365
url: /cs/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() metoda


Vypočítá průměr sekvence číselných hodnot.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### Návratová hodnota

Průměr hodnot v sekvenci.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) metoda


Vypočítá průměr sekvence hodnot, které jsou získány voláním transformační funkce na každém prvku vstupní sekvence.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ResultType | Typ hodnoty vrácené selektorem. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Transformace funkce, která se použije na každý prvek. |

### Návratová hodnota

Průměr promítnutých hodnot.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) metoda




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Viz také

* Třída [IEnumerable](../)
* Třída [Func](../../../system/func/)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)