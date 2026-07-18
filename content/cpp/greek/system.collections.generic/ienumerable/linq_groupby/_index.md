---
title: LINQ_GroupBy()
second_title: Αναφορά API του Aspose.Slides για C++
description: Ομαδοποιεί τα στοιχεία μιας ακολουθίας.
type: docs
weight: 287
url: /el/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) μέθοδος


Ομαδοποιεί τα στοιχεία μιας ακολουθίας.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Key | Ο τύπος του κλειδιού που επιστρέφεται από το keyPredicate |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Συνάρτηση για την εξαγωγή του κλειδιού για κάθε στοιχείο. |

### Τιμή Επιστροφής

Ένα [IEnumerable](../) που περιέχει μια ακολουθία αντικειμένων και ένα κλειδί

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) μέθοδος


Ομαδοποιεί τα στοιχεία μιας ακολουθίας.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Key | Ο τύπος του κλειδιού που επιστρέφεται από το keyPredicate |
| Element | Ο τύπος του στοιχείου που επιστρέφεται από το elementSelector |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Συνάρτηση για την εξαγωγή του κλειδιού για κάθε στοιχείο. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Συνάρτηση για την εξαγωγή του κλειδιού τιμής για κάθε στοιχείο. |

### Τιμή Επιστροφής

Ένα [IEnumerable](../) που περιέχει μια ακολουθία αντικειμένων και ένα κλειδί

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) μέθοδος




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) μέθοδος




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)