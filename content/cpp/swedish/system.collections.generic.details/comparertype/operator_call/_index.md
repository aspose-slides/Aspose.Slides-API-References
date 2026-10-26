---
title: operator()()
second_title: Aspose.Slides för C++ API-referens
description: Jämför värdetyper som implementerar IComparable-gränssnittet.
type: docs
weight: 1
url: /sv/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const metod


Jämför värdetyper som implementerar [IComparable](../../../system/icomparable/) gränssnitt.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Typ att jämföra. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const Q\& | Värde på vänster sida. |
| b | const Q\& | Värde på höger sida. |

### Returvärde

Sant om **a** anses vara mindre än **b**, annars falskt.

## ComparerType::operator()(const Q\&, const Q\&) const metod


Jämför primitiva värdetyper och objekt som inte implementerar [IComparable](../../../system/icomparable/) gränssnitt.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Typ att jämföra. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const Q\& | Värde på vänster sida. |
| b | const Q\& | Värde på höger sida. |

### Returvärde

Sant om **a** anses vara mindre än **b**, annars falskt.

## ComparerType::operator()(const Q\&, const Q\&) const metod


Jämför flyttalstyper.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Typ att jämföra. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const Q\& | Värde på vänster sida. |
| b | const Q\& | Värde på höger sida. |

### Returvärde

Sant om **a** anses vara mindre än **b**, annars falskt.

## Se även

* Klass [IComparable](../../../system/icomparable/)
* Struktur [has_method_compareto](../../has_method_compareto/)
* Struktur [ComparerType](../)
* Namnrymd [System::Collections::Generic::Details](../../)
* Bibliotek [Aspose.Slides](../../../)