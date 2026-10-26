---
title: CastEnumerableTo()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Εκτελεί τη ρητή μετατροπή των στοιχείων του συγκεκριμένου αντικειμένου enumerable σε διαφορετικό τύπο.
type: docs
weight: 2926
url: /el/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) συνάρτηση

Εκτελεί τη ρητή μετατροπή των στοιχείων του συγκεκριμένου αντικειμένου enumerable σε διαφορετικό τύπο.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| To | Ο τύπος στον οποίο θα γίνει στατική μετατροπή των στοιχείων του αντικειμένου enumerable |
| From | Ο τύπος του αντικειμένου enumerable |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumerable | const From\& | Αντικείμενο enumerable που περιέχει τα στοιχεία προς μετατροπή |

### Αξία Επιστροφής

Ένας δείκτης σε νέα συλλογή που περιέχει στοιχεία τύπου **To** ισοδύναμα με τα στοιχεία του **enumerable**

## System::CastEnumerableTo(const From\&) συνάρτηση

Εκτελεί τη ρητή μετατροπή των στοιχείων του συγκεκριμένου αντικειμένου enumerable σε διαφορετικό τύπο.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| To | Ο τύπος στον οποίο θα γίνει στατική μετατροπή των στοιχείων του αντικειμένου enumerable |
| From | Ο τύπος του αντικειμένου enumerable |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enumerable | const From\& | είναι κληρονόμος του αντικειμένου Enumerable με ορισμένη μέθοδο get_Count και περιέχει τα στοιχεία προς μετατροπή |

### Αξία Επιστροφής

Ένας δείκτης σε νέα συλλογή που περιέχει στοιχεία τύπου **To** ισοδύναμα με τα στοιχεία του **enumerable**

## Δείτε επίσης

* Κλάση [ListPtr](../../system.collections.generic/listptr/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)