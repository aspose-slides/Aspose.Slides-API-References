---
title: LINQ_Max()
second_title: Aspose.Slides pro C++ – API reference
description: Vyvolá transformační funkci na každém prvku obecné sekvence a vrátí maximální výslednou hodnotu.
type: docs
weight: 352
url: /cs/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) metoda


Vyvolá transformační funkci na každém prvku obecné sekvence a vrátí maximální výslednou hodnotu.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ResultType | Typ hodnoty vrácené selector. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Transformace funkce, která se použije na každý prvek. |

### Návratová hodnota

Maximální hodnota v sekvenci.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) metoda




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Viz také

* Třída [Func](../../../system/func/)
* Třída [IEnumerable](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)