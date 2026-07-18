---
title: operator!=()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Καθορίζει εάν το τρέχον και το καθορισμένο αντικείμενα TypeInfo δεν είναι ίσα.
type: docs
weight: 456
url: /el/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const μέθοδος

Καθορίζει αν το τρέχον και το καθορισμένο [TypeInfo](../) αντικείμενα δεν είναι ίσα.

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | Το [TypeInfo](../) αντικείμενο για σύγκριση |

### Τιμή Επιστροφής

True εάν τα hash των αντικειμένων δεν είναι ίσα, διαφορετικά - false

## TypeInfo::operator!=(std::nullptr_t) const μέθοδος

Καθορίζει εάν το τρέχον [TypeInfo](../) αντικείμενο δεν είναι null-object, δηλαδή αντιπροσωπεύει κάποιο τύπο.

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```

### Τιμή Επιστροφής

True εάν το τρέχον [TypeInfo](../) αντικείμενο δεν είναι null-object, διαφορετικά - false

## Δείτε επίσης

* Κλάση [TypeInfo](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)