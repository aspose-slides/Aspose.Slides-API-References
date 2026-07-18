---
title: Contains()
second_title: Αναφορά API του Aspose.Slides για C++
description: Ελέγχει εάν ένα αμετάβλητο span περιέχει μια συγκεκριμένη τιμή.
type: docs
weight: 40
url: /el/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) συνάρτηση

Ελέγχει εάν ένα αμετάβλητο span περιέχει μια συγκεκριμένη τιμή.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### Παράμετρα προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | The type of elements in the span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to search for |

### Τιμή επιστροφής

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) συνάρτηση

Ελέγχει εάν ένα μεταβλητό span περιέχει μια συγκεκριμένη τιμή.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### Παράμετρα προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | The type of elements in the span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value | const T\& | The value to search for |

### Τιμή επιστροφής

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) συνάρτηση

Ελέγχει εάν ένα span χαρακτήρων περιέχει ένα άλλο span χαρακτήρων με τους καθορισμένους κανόνες σύγκρισης.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### Τιμή επιστροφής

true if value is found in span, false otherwise

## Δείτε επίσης

* Απαρίθμηση [StringComparison](../../system/stringcomparison/)
* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)