---
title: operator()()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkingsfunctie voor typen met operator < beschikbaar.
type: docs
weight: 27
url: /nl/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const method


[Comparison](../../../system/comparison/) functie voor typen met operator < beschikbaar.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### Retourwaarde

True if **x** is considered less than **y**, false otherwise.

## ComparerAdapter::operator()(const Q\&, const Q\&) const method


[Comparison](../../../system/comparison/) functie voor typen met operator < niet beschikbaar.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### Retourwaarde

True if comparator is set and **x** is considered less than **y**, false otherwise.

## Zie ook

* Struct [ComparerAdapter](../)
* Naamruimte [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)