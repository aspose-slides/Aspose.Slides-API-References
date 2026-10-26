---
title: Is()
second_title: Aspose.Slides για C++ Αναφορά API
description: Υλοποιεί τη μετάφραση του μοτίβου δήλωσης 'is'.
type: docs
weight: 2276
url: /el/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) συνάρτηση


Υλοποιεί τη μετάφραση του μοτίβου δήλωσης 'is'.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| PatternT | τύπος προς έλεγχο. |
| ExpressionT | τύπος αριστερής έκφρασης. |
| ResultT | τύπος της έκφρασης αποτελέσματος. |

### Επιχειρήματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | const ExpressionT\& | έκφραση που θα ελεγχθεί. |
| result | ResultT\& | μεταβλητή στην οποία θα ανατεθεί ο ελεγμένος τύπος. |

### Τιμή επιστροφής

true εάν ο έλεγχος τύπου είναι επιτυχής, false διαφορετικά.

## System::Is(const ExpressionT\&, const ConstantT\&) συνάρτηση


Υλοποιεί τη μετάφραση του μοτίβου σταθεράς 'is'.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ExpressionT | τύπος αριστερής έκφρασης. |
| ConstantT | τύπος της σταθερής έκφρασης. |

### Επιχειρήματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | const ExpressionT\& | έκφραση που θα ελεγχθεί. |
| constant | const ConstantT\& | έκφραση που θα συγκριθεί με την αριστερή. |

### Τιμή επιστροφής

true εάν ο έλεγχος τύπου είναι επιτυχής, false διαφορετικά.

## System::Is(const E\&, const A\&) συνάρτηση


Λειτουργία αντιστοίχισης κορυφαίου επιπέδου. Εφαρμόζει ένα μοτίβο σε μια τιμή.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| A | Τύπος μοτίβου (πρέπει να κληρονομεί από Details::Pattern). |
| E | Τύπος της τιμής προς αντιστοίχιση. |

### Επιχειρήματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| e | const E\& | τιμή για αντιστοίχιση. |
| a | const A\& | μοτίβο που θα εφαρμοστεί. |

### Τιμή επιστροφής

true εάν το μοτίβο αντιστοιχεί στην τιμή, false διαφορετικά.

## Δες επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)