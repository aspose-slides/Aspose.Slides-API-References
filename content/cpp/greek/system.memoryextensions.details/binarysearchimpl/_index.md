---
title: BinarySearchImpl()
second_title: Aspose.Slides για C++ API Αναφορά
description: Κοινή υλοποίηση δυαδικής αναζήτησης.
type: docs
weight: 118
url: /el/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) συνάρτηση

Κοινή υλοποίηση δυαδικής αναζήτησης.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος των στοιχείων στο span |
| TValue | Τύπος της τιμής προς αναζήτηση |
| TCompareFunc | Τύπος συνάρτησης για σύγκριση |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span προς αναζήτηση |
| value | const TValue\& | Η τιμή προς αναζήτηση |
| compareFunc | TCompareFunc | Συνάρτηση που συγκρίνει την τιμή με το στοιχείο του span και επιστρέφει **int32_t** (-1, 0, 1) |

### Τιμή επιστροφής

Δείκτης του ευρεθέντος στοιχείου ή το δυαδικό συμπλήρωμα του σημείου εισαγωγής

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Χώρος ονομάτων [System::MemoryExtensions::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)