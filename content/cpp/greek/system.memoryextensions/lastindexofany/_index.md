---
title: LastIndexOfAny()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εντοπίζει την τελευταία εμφάνιση οποιασδήποτε από τις τρεις καθορισμένες τιμές μέσα σε ένα span.
type: docs
weight: 222
url: /el/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) συνάρτηση

Εντοπίζει την τελευταία εμφάνιση οποιασδήποτε από τις τρεις καθορισμένες τιμές μέσα σε ένα span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span μέσα στο οποίο γίνεται η αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή προς αναζήτηση |
| value1 | const T\& | Η δεύτερη τιμή προς αναζήτηση |
| value2 | const T\& | Η τρίτη τιμή προς αναζήτηση |

### Τιμή Επιστροφής

Ο δείκτης με βάση το μηδέν της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) συνάρτηση

Εντοπίζει την τελευταία εμφάνιση οποιασδήποτε από τις τρεις καθορισμένες τιμές μέσα σε ένα μεταβλητό span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span μέσα στο οποίο γίνεται η αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή προς αναζήτηση |
| value1 | const T\& | Η δεύτερη τιμή προς αναζήτηση |
| value2 | const T\& | Η τρίτη τιμή προς αναζήτηση |

### Τιμή Επιστροφής

Ο δείκτης με βάση το μηδέν της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) συνάρτηση

Εντοπίζει την τελευταία εμφάνιση οποιασδήποτε από τις δύο καθορισμένες τιμές μέσα σε ένα span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span μέσα στο οποίο γίνεται η αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή προς αναζήτηση |
| value1 | const T\& | Η δεύτερη τιμή προς αναζήτηση |

### Τιμή Επιστροφής

Ο δείκτης με βάση το μηδέν της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) συνάρτηση

Εντοπίζει την τελευταία εμφάνιση οποιασδήποτε από τις δύο καθορισμένες τιμές μέσα σε ένα μεταβλητό span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span μέσα στο οποίο γίνεται η αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή προς αναζήτηση |
| value1 | const T\& | Η δεύτερη τιμή προς αναζήτηση |

### Τιμή Επιστροφής

Ο δείκτης με βάση το μηδέν της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Εντοπίζει την τελευταία εμφάνιση οποιασδήποτε τιμής από μια ακολουθία μέσα σε ένα span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span μέσα στο οποίο γίνεται η αναζήτηση |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Η ακολουθία τιμών προς αναζήτηση |

### Τιμή Επιστροφής

Ο δείκτης με βάση το μηδέν της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Εντοπίζει την τελευταία εμφάνιση οποιασδήποτε τιμής από μια ακολουθία μέσα σε ένα μεταβλητό span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span μέσα στο οποίο γίνεται η αναζήτηση |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Η ακολουθία τιμών προς αναζήτηση |

### Τιμή Επιστροφής

Ο δείκτης με βάση το μηδέν της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) συνάρτηση

Εντοπίζει την τελευταία εμφάνιση οποιασδήποτε τιμής από μια μεταβλητή ακολουθία μέσα σε ένα μεταβλητό span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span μέσα στο οποίο γίνεται η αναζήτηση |
| values | const [Span](../../system/span/)\<T\>\& | Η ακολουθία τιμών προς αναζήτηση |

### Τιμή Επιστροφής

Ο δείκτης με βάση το μηδέν της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)