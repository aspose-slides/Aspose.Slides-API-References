---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides για C++ API Reference
description: Βοηθητική συνάρτηση για τον καθορισμό εάν συγκεκριμένη κλάση έχει operator ==.
type: docs
weight: 235
url: /el/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) συνάρτηση

Βοηθητική συνάρτηση για την καθορισμό εάν μια συγκεκριμένη κλάση έχει operator ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος για έλεγχο. |
| Dummy | Ψεύτικο όρισμα για μαγικά SFINAE. |

### Τιμή Επιστροφής

Τιμή του std::true_type εάν υπάρχει operator == και false διαφορετικά.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) συνάρτηση

Βοηθητική συνάρτηση για την καθορισμό εάν μια συγκεκριμένη κλάση έχει operator ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### Τιμή Επιστροφής

Τιμή του std::true_type εάν υπάρχει operator == και false διαφορετικά.

## Δείτε επίσης

* Χώρος ονομάτων [System::Collections::Generic::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)