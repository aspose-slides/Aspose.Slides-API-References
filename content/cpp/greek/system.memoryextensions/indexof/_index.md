---
title: IndexOf()
second_title: Aspose.Slides για C++ Αναφορά API
description: Εντοπίζει το ευρετήριο μιας τιμής ReadOnlySpan<T> σε ένα άλλο ReadOnlySpan<T>
type: docs
weight: 144
url: /el/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Εντοπίζει το ευρετήριο μιας τιμής ReadOnlySpan<T> σε ένα άλλο ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span στο οποίο γίνεται η αναζήτηση |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span που αναζητείται |

### Τιμή Επιστροφής

Το μηδενικό-βασισμένο ευρετήριο της πρώτης εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) συνάρτηση

Εντοπίζει το ευρετήριο μιας μονής τιμής σε ένα ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span στο οποίο γίνεται η αναζήτηση |
| value | const T\& | Η τιμή που αναζητείται |

### Τιμή Επιστροφής

Το μηδενικό-βασισμένο ευρετήριο της πρώτης εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Εντοπίζει το ευρετήριο μιας τιμής ReadOnlySpan<T> σε ένα Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span στο οποίο γίνεται η αναζήτηση |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span που αναζητείται |

### Τιμή Επιστροφής

Το μηδενικό-βασισμένο ευρετήριο της πρώτης εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) συνάρτηση

Εντοπίζει το ευρετήριο μιας μονής τιμής σε ένα Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span στο οποίο γίνεται η αναζήτηση |
| value | const T\& | Η τιμή που αναζητείται |

### Τιμή Επιστροφής

Το μηδενικό-βασισμένο ευρετήριο της πρώτης εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) συνάρτηση

Εντοπίζει το ευρετήριο μιας τιμής ReadOnlySpan<char16_t> σε ένα ReadOnlySpan<char16_t> με StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το span στο οποίο γίνεται η αναζήτηση |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Η τιμή που αναζητείται |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Ο τύπος σύγκρισης συμβολοσειράς που θα χρησιμοποιηθεί |

### Τιμή Επιστροφής

Το μηδενικό-βασισμένο ευρετήριο της πρώτης εμφάνισης, ή -1 αν δεν βρεθεί

## Δείτε επίσης

* Enum [StringComparison](../../system/stringcomparison/)
* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)