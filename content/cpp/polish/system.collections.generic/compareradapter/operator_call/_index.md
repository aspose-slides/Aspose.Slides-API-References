---
title: operator()()
second_title: Aspose.Slides dla C++ dokumentacja API
description: Funkcja porównująca dla typów z dostępnym operatorem <.
type: docs
weight: 27
url: /pl/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const metoda


[Comparison](../../../system/comparison/) funkcja dla typów z dostępnym operatorem <.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ porównywany; szablon określający dostępność konwersji typów. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const Q\& | Pierwsza wartość do porównania. |
| y | const Q\& | Druga wartość do porównania. |

### Wartość zwracana

Prawda, jeśli **x** jest uznawany za mniejszy niż **y**, w przeciwnym razie fałsz.

## ComparerAdapter::operator()(const Q\&, const Q\&) const metoda


[Comparison](../../../system/comparison/) funkcja dla typów bez dostępnego operatora <.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ porównywany; szablon określający dostępność konwersji typów. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const Q\& | Pierwsza wartość do porównania. |
| y | const Q\& | Druga wartość do porównania. |

### Wartość zwracana

Prawda, jeśli komparator jest ustawiony i **x** jest uznawany za mniejszy niż **y**, w przeciwnym razie fałsz.

## Zobacz także

* Struktura [ComparerAdapter](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)