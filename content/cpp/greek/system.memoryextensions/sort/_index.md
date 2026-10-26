---
title: Sort()
second_title: Αναφορά API Aspose.Slides για C++
description: Ταξινομεί ένα Span χρησιμοποιώντας έναν προσαρμοσμένο συγκριτή.
type: docs
weight: 339
url: /el/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) συνάρτηση


Ταξινομεί ένα [Span](../../system/span/) χρησιμοποιώντας έναν προσαρμοσμένο συγκριτή.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |
| TComparer | Ο τύπος του αντικειμένου συγκριτή |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span προς ταξινόμηση |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Έξυπνος δείκτης στο αντικείμενο συγκριτή για τη σύγκριση στοιχείων |

## System::MemoryExtensions::Sort(Span\<T\>\&) συνάρτηση


Ταξινομεί ένα [Span](../../system/span/) χρησιμοποιώντας την προεπιλεγμένη σύγκριση.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Το span προς ταξινόμηση |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) συνάρτηση


Ταξινομεί ζεύγη κλειδιού-τιμής χρησιμοποιώντας έναν προσαρμοσμένο συγκριτή (κλειδιά και τιμές ταξινομούνται μαζί)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Ο τύπος των κλειδιών |
| TValue | Ο τύπος των τιμών |
| TComparer | Ο τύπος του αντικειμένου συγκριτή |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Το span των κλειδιών προς ταξινόμηση |
| values | [Span](../../system/span/)\<TValue\>\& | Το span των τιμών προς ταξινόμηση (διατηρώντας την αντιστοιχία με τα κλειδιά) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Έξυπνος δείκτης στο αντικείμενο συγκριτή για τη σύγκριση κλειδιών |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) συνάρτηση


Ταξινομεί ζεύγη κλειδιού-τιμής χρησιμοποιώντας έναν αντιπρόσωπο σύγκρισης.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Ο τύπος των κλειδιών |
| TValue | Ο τύπος των τιμών |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Το span των κλειδιών προς ταξινόμηση |
| values | [Span](../../system/span/)\<TValue\>\& | Το span των τιμών προς ταξινόμηση |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) αντιπρόσωπος για τη σύγκριση κλειδιών |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) συνάρτηση


Ταξινομεί ζεύγη κλειδιού-τιμής χρησιμοποιώντας την προεπιλεγμένη σύγκριση.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Ο τύπος των κλειδιών |
| TValue | Ο τύπος των τιμών |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Το span των κλειδιών προς ταξινόμηση |
| values | [Span](../../system/span/)\<TValue\>\& | Το span των τιμών προς ταξινόμηση |

## Δείτε επίσης

* Τύπος [SharedPtr](../../system/sharedptr/)
* Κλάση [Span](../../system/span/)
* Κλάση [Comparison](../../system/comparison/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)