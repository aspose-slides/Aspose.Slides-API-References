---
title: Equals()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει την ισότητα της καθορισμένης τιμής χρησιμοποιώντας τον τελεστή ==().
type: docs
weight: 66
url: /el/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) συνάρτηση

Καθορίζει την ισότητα της καθορισμένης τιμής χρησιμοποιώντας [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| The | τύπος των τιμών που συγκρίνονται |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value1 | T | Το πρώτο σύγκριμα |
| value2 | T | Το δεύτερο σύγκριμα |

### Τιμή επιστροφής

Αληθές αν η καθορισμένη τιμή είναι ίση όπως καθορίζεται από [operator==()](../../system/operator_equal_equal/), διαφορετικά - ψευδές

## System::BoxedValueDetail::Equals(T, T) συνάρτηση

Καθορίζει την ισότητα της καθορισμένης τιμής χρησιμοποιώντας τη μέθοδο [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| The | τύπος των τιμών που συγκρίνονται |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value1 | T | Το πρώτο σύγκριμα |
| value2 | T | Το δεύτερο σύγκριμα |

### Τιμή επιστροφής

Αληθές αν η καθορισμένη τιμή είναι ίση όπως καθορίζεται από τη μέθοδο [Equals()](./), διαφορετικά - ψευδές

## Δείτε επίσης

* Χώρος ονομάτων [System::BoxedValueDetail](../)
* Βιβλιοθήκη [Aspose.Slides](../../)