---
title: operator()()
second_title: Aspose.Slides για C++ API Αναφορά
description: Συνάρτηση σύγκρισης για τύπους με διαθέσιμο τελεστή <.
type: docs
weight: 27
url: /el/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const method


[Comparison](../../../system/comparison/) συνάρτηση για τύπους με διαθέσιμο τελεστή <.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### Τιμή Επιστροφής

Αληθές εάν το **x** θεωρείται μικρότερο από το **y**, ψευδές διαφορετικά.

## ComparerAdapter::operator()(const Q\&, const Q\&) const method


[Comparison](../../../system/comparison/) συνάρτηση για τύπους χωρίς διαθέσιμο τελεστή <.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### Τιμή Επιστροφής

Αληθές εάν ο συγκριτής είναι ορισμένος και το **x** θεωρείται μικρότερο από το **y**, ψευδές διαφορετικά.

## Δείτε επίσης

* Struct [ComparerAdapter](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)