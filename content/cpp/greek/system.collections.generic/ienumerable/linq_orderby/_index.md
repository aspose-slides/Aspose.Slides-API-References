---
title: LINQ_OrderBy()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ταξινομεί τα στοιχεία μιας ακολουθίας σε αύξουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector.
type: docs
weight: 209
url: /el/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) μέθοδος


Ταξινομεί τα στοιχεία μιας ακολουθίας σε αύξουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| keySelector | Μια συνάρτηση για την εξαγωγή ενός κλειδιού από ένα στοιχείο. |

### Τιμή επιστροφής

Ένα IOrderedEnumerable του οποίου τα στοιχεία ταξινομούνται σύμφωνα με ένα κλειδί

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) μέθοδος




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Βλέπε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Κλάση [Func](../../../system/func/)
* Κλάση [IEnumerable](../)
* Ονομαχώρος [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)