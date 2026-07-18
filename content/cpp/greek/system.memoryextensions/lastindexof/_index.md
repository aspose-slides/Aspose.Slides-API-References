---
title: LastIndexOf()
second_title: Aspose.Slides για C++ API Αναφορά
description: Βρίσκει την τελευταία εμφάνιση μιας ακολουθίας μέσα σε ένα span.
type: docs
weight: 209
url: /el/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση


Βρίσκει την τελευταία εμφάνιση μιας ακολουθίας μέσα σε ένα span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span στο οποίο θα γίνει η αναζήτηση |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Η ακολουθία που θα αναζητηθεί |

### Τιμή επιστροφής

Ο δείκτης μηδενικής βάσης της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) συνάρτηση


Βρίσκει την τελευταία εμφάνιση μίας μοναδικής τιμής μέσα σε ένα span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span στο οποίο θα γίνει η αναζήτηση |
| value | const T\& | Η τιμή που θα αναζητηθεί |

### Τιμή επιστροφής

Ο δείκτης μηδενικής βάσης της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση


Βρίσκει την τελευταία εμφάνιση μιας ακολουθίας μέσα σε ένα μεταβλητό span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span στο οποίο θα γίνει η αναζήτηση |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Η ακολουθία που θα αναζητηθεί |

### Τιμή επιστροφής

Ο δείκτης μηδενικής βάσης της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) συνάρτηση


Βρίσκει την τελευταία εμφάνιση μίας μοναδικής τιμής μέσα σε ένα μεταβλητό span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span στο οποίο θα γίνει η αναζήτηση |
| value | const T\& | Η τιμή που θα αναζητηθεί |

### Τιμή επιστροφής

Ο δείκτης μηδενικής βάσης της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) συνάρτηση


Βρίσκει την τελευταία εμφάνιση μίας τιμής μέσα σε ένα span χρησιμοποιώντας την καθορισμένη σύγκριση συμβολοσειρών.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το span στο οποίο θα γίνει η αναζήτηση |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Η τιμή που θα αναζητηθεί |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Ο τύπος σύγκρισης συμβολοσειρών που θα εκτελεστεί |

### Τιμή επιστροφής

Ο δείκτης μηδενικής βάσης της τελευταίας εμφάνισης, ή -1 αν δεν βρεθεί

## Δείτε επίσης

* Απαρίθμηση [StringComparison](../../system/stringcomparison/)
* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)