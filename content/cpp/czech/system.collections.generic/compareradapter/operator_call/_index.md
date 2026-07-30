---
title: operator()()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Porovnávací funkce pro typy, u nichž je k dispozici operátor <.
type: docs
weight: 27
url: /cs/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const metoda

[Comparison](../../../system/comparison/) funkce pro typy, u nichž je k dispozici operátor <.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### Návratová hodnota

True, pokud je **x** považováno za menší než **y**, jinak false.

## ComparerAdapter::operator()(const Q\&, const Q\&) const metoda

[Comparison](../../../system/comparison/) funkce pro typy, u nichž operátor < není k dispozici.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### Návratová hodnota

True, pokud je komparátor nastaven a **x** je považováno za menší než **y**, jinak false.

## Viz také

* Struct [ComparerAdapter](../)
* jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)