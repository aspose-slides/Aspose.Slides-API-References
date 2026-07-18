---
title: BinarySearch()
second_title: Αναφορά API Aspose.Slides για C++
description: Εκτελεί δυαδική αναζήτηση σε ένα ταξινομημένο span.
type: docs
weight: 14
url: /el/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) function


Εκτελεί δυαδική αναζήτηση σε ένα ταξινομημένο span.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |
| TComparable | Ο τύπος της συγκρίσιμης τιμής |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το ταξινομημένο span για αναζήτηση |
| comparable | const TComparable\& | Η τιμή που θα αναζητηθεί |

### Τιμή επιστροφής

Δείκτης του ευρεθέντος στοιχείου ή δυαδική συμπλήρωση του σημείου εισαγωγής εάν δεν βρεθεί

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) function


Εκτελεί δυαδική αναζήτηση σε ένα ταξινομημένο span χρησιμοποιώντας προσαρμοσμένο συγκριτή.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |
| TComparer | Ο τύπος του συγκριτή |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το ταξινομημένο span για αναζήτηση |
| value | const T\& | Η τιμή που θα αναζητηθεί |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Ο συγκριτής που θα χρησιμοποιηθεί για συγκρίσεις |

### Τιμή επιστροφής

Δείκτης του ευρεθέντος στοιχείου ή δυαδική συμπλήρωση του σημείου εισαγωγής εάν δεν βρεθεί

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) function


Εκτελεί δυαδική αναζήτηση σε ένα μεταβλητό ταξινομημένο span.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |
| TComparable | Ο τύπος της συγκρίσιμης τιμής |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το ταξινομημένο span για αναζήτηση |
| comparable | const TComparable\& | Η τιμή που θα αναζητηθεί |

### Τιμή επιστροφής

Δείκτης του ευρεθέντος στοιχείου ή δυαδική συμπλήρωση του σημείου εισαγωγής εάν δεν βρεθεί

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) function


Εκτελεί δυαδική αναζήτηση σε ένα μεταβλητό ταξινομημένο span χρησιμοποιώντας προσαρμοσμένο συγκριτή.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |
| TComparer | Ο τύπος του συγκριτή |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το ταξινομημένο span για αναζήτηση |
| value | const T\& | Η τιμή που θα αναζητηθεί |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Ο συγκριτής που θα χρησιμοποιηθεί για συγκρίσεις |

### Τιμή επιστροφής

Δείκτης του ευρεθέντος στοιχείου ή δυαδική συμπλήρωση του σημείου εισαγωγής εάν δεν βρεθεί

## Δείτε επίσης

* Typedef [SharedPtr](../../system/sharedptr/)
* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)