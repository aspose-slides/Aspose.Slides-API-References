---
title: operator()()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává typy hodnot implementující rozhraní IComparable.
type: docs
weight: 1
url: /cs/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const metoda

Porovnává typy hodnot implementující rozhraní [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Typ k porovnání. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | const Q\& | Hodnota LHS. |
| b | const Q\& | Hodnota RHS. |

### Návratová hodnota

Vrátí true, pokud je **a** považováno za menší než **b**, jinak false.

## ComparerType::operator()(const Q\&, const Q\&) const metoda

Porovnává primitivní typy hodnot a objekty neimplementující rozhraní [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Typ k porovnání. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | const Q\& | Hodnota LHS. |
| b | const Q\& | Hodnota RHS. |

### Návratová hodnota

Vrátí true, pokud je **a** považováno za menší než **b**, jinak false.

## ComparerType::operator()(const Q\&, const Q\&) const metoda

Porovnává typy s plovoucí desetinnou čárkou.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Typ k porovnání. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | const Q\& | Hodnota LHS. |
| b | const Q\& | Hodnota RHS. |

### Návratová hodnota

Vrátí true, pokud je **a** považováno za menší než **b**, jinak false.

## Viz také

* Třída [IComparable](../../../system/icomparable/)
* Struktura [has_method_compareto](../../has_method_compareto/)
* Struktura [ComparerType](../)
* Jmenný prostor [System::Collections::Generic::Details](../../)
* Knihovna [Aspose.Slides](../../../)