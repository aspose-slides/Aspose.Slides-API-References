---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ταξινομεί τα στοιχεία μιας ακολουθίας σε φθίνουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector.
type: docs
weight: 222
url: /el/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) μέθοδος

Ταξινομεί τα στοιχεία μιας ακολουθίας σε φθίνουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέχθηκαν από το keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| keySelector | Μια συνάρτηση για την εξαγωγή ενός κλειδιού από ένα στοιχείο. |

### Τιμή Επιστροφής

Ένα IOrderedEnumerable του οποίου τα στοιχεία είναι ταξινομημένα σε φθίνουσα σειρά του κλειδιού

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) μέθοδος

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Κλάση [Func](../../../system/func/)
* Κλάση [IEnumerable](../)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)