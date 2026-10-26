---
title: SequenceEqual()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει εάν δύο ReadOnlySpans περιέχουν ταυτόστροφα στοιχεία στην ίδια σειρά.
type: docs
weight: 326
url: /el/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Καθορίζει εάν δύο ReadOnlySpans περιέχουν ταυτόστροφα στοιχεία στην ίδια σειρά.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στις ακολουθίες |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Η πρώτη ακολουθία για σύγκριση |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Η δεύτερη ακολουθία για σύγκριση |

### Τιμή επιστροφής

true αν οι ακολουθίες έχουν το ίδιο μήκος και όλα τα στοιχεία είναι ίσα, false διαφορετικά

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Καθορίζει εάν ένα [Span](../../system/span/) και [ReadOnlySpan](../../system/readonlyspan/) περιέχουν ταυτόστροφα στοιχεία στην ίδια σειρά.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στις ακολουθίες |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Η [Span](../../system/span/) για σύγκριση |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Η [ReadOnlySpan](../../system/readonlyspan/) για σύγκριση |

### Τιμή επιστροφής

true αν οι ακολουθίες έχουν το ίδιο μήκος και όλα τα στοιχεία είναι ίσα, false διαφορετικά

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function

Καθορίζει εάν δύο ReadOnlySpans περιέχουν ίσα στοιχεία χρησιμοποιώντας έναν προσαρμοσμένο συγκριτή.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στις ακολουθίες |
| TComparer | Ο τύπος του αντικειμένου συγκριτή |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Η πρώτη ακολουθία για σύγκριση |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Η δεύτερη ακολουθία για σύγκριση |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Έξυπνος δείκτης σε αντικείμενο συγκριτή για τη σύγκριση στοιχείων |

### Τιμή επιστροφής

true αν οι ακολουθίες έχουν το ίδιο μήκος και ο συγκριτής θεωρεί όλα τα στοιχεία ίσα, false διαφορετικά

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function

Καθορίζει εάν ένα [Span](../../system/span/) και [ReadOnlySpan](../../system/readonlyspan/) περιέχουν ίσα στοιχεία χρησιμοποιώντας έναν προσαρμοσμένο συγκριτή.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στις ακολουθίες |
| TComparer | Ο τύπος του αντικειμένου συγκριτή |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Η [Span](../../system/span/) για σύγκριση |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Η [ReadOnlySpan](../../system/readonlyspan/) για σύγκριση |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Έξυπνος δείκτης σε αντικείμενο συγκριτή για τη σύγκριση στοιχείων |

### Τιμή επιστροφής

true αν οι ακολουθίες έχουν το ίδιο μήκος και ο συγκριτής θεωρεί όλα τα στοιχεία ίσα, false διαφορετικά

## Δείτε επίσης

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)