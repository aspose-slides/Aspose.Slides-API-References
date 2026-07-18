---
title: SequenceCompareTo()
second_title: Aspose.Slides για C++ API Αναφορά
description: Συγκρίνει δύο ReadOnlySpans λεξικογραφικά.
type: docs
weight: 313
url: /el/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Συγκρίνει δύο ReadOnlySpan λεξικογραφικά.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το πρώτο span για σύγκριση |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το δεύτερο span για σύγκριση |

### Τιμή Επιστροφής

- 1 εάν span < other, 0 εάν span == other, 1 εάν span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Συγκρίνει ένα [Span](../../system/span/) και [ReadOnlySpan](../../system/readonlyspan/) λεξικογραφικά.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το [Span](../../system/span/) για σύγκριση |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το [ReadOnlySpan](../../system/readonlyspan/) για σύγκριση |

### Τιμή Επιστροφής

- 1 εάν span < other, 0 εάν span == other, 1 εάν span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function

Συγκρίνει ένα [ReadOnlySpan](../../system/readonlyspan/) και [Span](../../system/span/) λεξικογραφικά.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το [ReadOnlySpan](../../system/readonlyspan/) για σύγκριση |
| other | const [Span](../../system/span/)\<T\>\& | Το [Span](../../system/span/) για σύγκριση |

### Τιμή Επιστροφής

- 1 εάν span < other, 0 εάν span == other, 1 εάν span > other

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)