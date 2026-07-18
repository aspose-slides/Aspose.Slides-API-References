---
title: operator()()
second_title: Aspose.Slides για C++ Αναφορά API
description: Συγκρίνει τύπους τιμών που υλοποιούν τη διασύνδεση IComparable.
type: docs
weight: 1
url: /el/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const μέθοδος

Συγκρίνει τύπους τιμών που υλοποιούν τη διασύνδεση [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Τύπος προς σύγκριση. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | const Q\& | Τιμή LHS. |
| b | const Q\& | Τιμή RHS. |

### Τιμή Επιστροφής

Αληθές εάν το **a** θεωρείται μικρότερο από το **b**, ψευδές διαφορετικά.

## ComparerType::operator()(const Q\&, const Q\&) const μέθοδος

Συγκρίνει πρωτόγονους τύπους τιμών και αντικείμενα που δεν υλοποιούν τη διασύνδεση [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Τύπος προς σύγκριση. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | const Q\& | Τιμή LHS. |
| b | const Q\& | Τιμή RHS. |

### Τιμή Επιστροφής

Αληθές εάν το **a** θεωρείται μικρότερο από το **b**, ψευδές διαφορετικά.

## ComparerType::operator()(const Q\&, const Q\&) const μέθοδος

Συγκρίνει τύπους κινητής υποδιαστολής.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Τύπος προς σύγκριση. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | const Q\& | Τιμή LHS. |
| b | const Q\& | Τιμή RHS. |

### Τιμή Επιστροφής

Αληθές εάν το **a** θεωρείται μικρότερο από το **b**, ψευδές διαφορετικά.

## Δείτε επίσης

* Κλάση [IComparable](../../../system/icomparable/)
* Δομή [has_method_compareto](../../has_method_compareto/)
* Δομή [ComparerType](../)
* Χώρος ονομάτων [System::Collections::Generic::Details](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)