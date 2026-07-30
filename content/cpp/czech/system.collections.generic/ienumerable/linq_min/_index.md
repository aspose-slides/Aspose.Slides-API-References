---
title: LINQ_Min()
second_title: Aspose.Slides pro referenci API C++
description: Vyvolá transformační funkci na každém prvku obecné sekvence a vrátí minimální výslednou hodnotu.
type: docs
weight: 339
url: /cs/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) metoda


Vyvolá transformační funkci na každém prvku obecné sekvence a vrátí minimální výslednou hodnotu.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ResultType | Typ hodnoty vrácené selektorem. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Transformovací funkce aplikovaná na každý prvek. |

### Návratová hodnota

Minimální hodnota v sekvenci.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) metoda




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Viz také

* Třída [Func](../../../system/func/)
* Třída [IEnumerable](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)