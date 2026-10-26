---
title: operator()()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Porównuje typy wartości implementujące interfejs IComparable.
type: docs
weight: 1
url: /pl/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const metoda

Porównuje typy wartości implementujące interfejs [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ do porównania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const Q\& | Wartość LHS. |
| b | const Q\& | Wartość RHS. |

### Wartość zwracana

True jeśli **a** jest uważane za mniejsze niż **b**, false w przeciwnym razie.

## ComparerType::operator()(const Q\&, const Q\&) const metoda

Porównuje prymitywne typy wartości oraz obiekty nieimplementujące interfejsu [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ do porównania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const Q\& | Wartość LHS. |
| b | const Q\& | Wartość RHS. |

### Wartość zwracana

True jeśli **a** jest uważane za mniejsze niż **b**, false w przeciwnym razie.

## ComparerType::operator()(const Q\&, const Q\&) const metoda

Porównuje typy zmiennoprzecinkowe.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ do porównania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const Q\& | Wartość LHS. |
| b | const Q\& | Wartość RHS. |

### Wartość zwracana

True jeśli **a** jest uważane za mniejsze niż **b**, false w przeciwnym razie.

## Zobacz także

* Klasa [IComparable](../../../system/icomparable/)
* Struktura [has_method_compareto](../../has_method_compareto/)
* Struktura [ComparerType](../)
* Przestrzeń nazw [System::Collections::Generic::Details](../../)
* Biblioteka [Aspose.Slides](../../../)