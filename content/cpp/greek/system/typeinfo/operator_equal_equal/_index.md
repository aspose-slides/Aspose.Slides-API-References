---
title: operator==()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει εάν τα τρέχοντα και τα καθορισμένα TypeInfo αντικείμενα είναι ίσα.
type: docs
weight: 443
url: /el/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const μέθοδος

Καθορίζει εάν τα τρέχοντα και τα καθορισμένα [TypeInfo](../) αντικείμενα είναι ίσα.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | Το [TypeInfo](../) αντικείμενο για σύγκριση |

### Τιμή επιστροφής

Αληθής εάν τα hash των αντικειμένων είναι ίσα, διαφορετικά - ψευδής

## TypeInfo::operator==(std::nullptr_t) const μέθοδος

Καθορίζει εάν το τρέχον [TypeInfo](../) αντικείμενο είναι ένα null-object, δηλαδή δεν αντιπροσωπεύει κανέναν τύπο.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### Τιμή επιστροφής

Αληθής εάν το τρέχον [TypeInfo](../) αντικείμενο είναι ένα null-object, διαφορετικά - ψευδής

## Δείτε επίσης

* Κλάση [TypeInfo](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)