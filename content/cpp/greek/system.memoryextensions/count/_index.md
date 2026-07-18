---
title: Count()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετρά τις εμφανίσεις μιας τιμής σε ένα span μόνο για ανάγνωση.
type: docs
weight: 118
url: /el/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) συνάρτηση

Μετρά τις εμφανίσεις μιας τιμής σε ένα span μόνο για ανάγνωση.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span στο οποίο γίνεται η αναζήτηση |
| value | const T\& | Η τιμή που θα μετρηθεί |

### Τιμή επιστροφής

Ο αριθμός των φορών που εμφανίζεται η τιμή στο span

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Μετρά τις εμφανίσεις ενός span μέσα σε ένα άλλο span μόνο για ανάγνωση.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span στο οποίο γίνεται η αναζήτηση |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span του οποίου θα μετρηθούν οι εμφανίσεις |

### Τιμή επιστροφής

Ο αριθμός των φορών που εμφανίζεται η τιμή στο span

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) συνάρτηση

Μετρά τις εμφανίσεις μιας μοναδικής τιμής σε ένα Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span στο οποίο γίνεται η αναζήτηση |
| value | const T\& | Η τιμή της οποίας θα μετρηθούν οι εμφανίσεις |

### Τιμή επιστροφής

Ο αριθμός των εμφανίσεων της τιμής στο span

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Μετρά τις εμφανίσεις ενός ReadOnlySpan<T> σε ένα Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span στο οποίο γίνεται η αναζήτηση |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span που περιέχει τις τιμές των οποίων θα μετρηθούν οι εμφανίσεις |

### Τιμή επιστροφής

Ο αριθμός των εμφανίσεων του span τιμών στο span-στόχο

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)