---
title: LINQ_ThenBy()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εκτελεί μια επακόλουθη ταξινόμηση των στοιχείων σε μια ακολουθία σε αύξουσα σειρά σύμφωνα με ένα κλειδί.
type: docs
weight: 27
url: /el/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method

Εκτελεί μια επακόλουθη ταξινόμηση των στοιχείων σε μια ακολουθία σε αύξουσα σειρά σύμφωνα με ένα κλειδί.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Key | Ο τύπος του κλειδιού που επιστρέφεται από το keySelector. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | Μια συνάρτηση για την εξαγωγή ενός κλειδιού από κάθε στοιχείο. |

### Τιμή επιστροφής

[System::Linq::IOrderedEnumerable](../) των οποίων τα στοιχεία ταξινομούνται σύμφωνα με ένα κλειδί.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IOrderedEnumerable](../)
* Κλάση [Func](../../../system/func/)
* Χώρος ονομάτων [System::Linq](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)