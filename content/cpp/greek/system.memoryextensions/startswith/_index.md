---
title: StartsWith()
second_title: Aspose.Slides για το API του C++
description: Ελέγχει εάν το span ξεκινά με την καθορισμένη τιμή.
type: docs
weight: 352
url: /el/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) συνάρτηση

Ελέγχει εάν το span ξεκινά με την καθορισμένη τιμή.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span που θα ελεγχθεί |
| value | const T\& | Η τιμή που θα ελεγχθεί στην αρχή του span |

### Τιμή επιστροφής

true εάν το span ξεκινά με την τιμή, false διαφορετικά

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Ελέγχει εάν το span ξεκινά με το καθορισμένο span τιμής.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span που θα ελεγχθεί |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span που περιέχει τις τιμές που θα ελεγχθούν στην αρχή |

### Τιμή επιστροφής

true εάν το span ξεκινά με το span τιμής, false διαφορετικά

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Ελέγχει εάν το μεταβλητό span ξεκινά με το span τιμής μόνο για ανάγνωση.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το μεταβλητό span που θα ελεγχθεί |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span μόνο για ανάγνωση που περιέχει τις τιμές που θα ελεγχθούν |

### Τιμή επιστροφής

true εάν το span ξεκινά με το span τιμής, false διαφορετικά

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) συνάρτηση

Ελέγχει εάν το span μόνο για ανάγνωση ξεκινά με το καθορισμένο μεταβλητό span τιμής.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span μόνο για ανάγνωση που θα ελεγχθεί |
| value | const [Span](../../system/span/)\<T\>\& | Το μεταβλητό span που περιέχει τις τιμές που θα ελεγχθούν |

### Τιμή επιστροφής

true εάν το span ξεκινά με το span τιμής, false διαφορετικά

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) συνάρτηση

Ελέγχει εάν το span χαρακτήρων ξεκινά με το καθορισμένο span τιμής χρησιμοποιώντας σύγκριση συμβολοσειράς.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το span χαρακτήρων που θα ελεγχθεί |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το span χαρακτήρων που περιέχει τις τιμές που θα ελεγχθούν |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Ο τύπος της σύγκρισης συμβολοσειρών που θα εκτελεστεί |

### Τιμή επιστροφής

true εάν το span ξεκινά με το span τιμής, false διαφορετικά

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) συνάρτηση

Ελέγχει εάν ένα span συμβολοσειράς ξεκινά με το καθορισμένο πίνακα χαρακτήρων.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | Το span συμβολοσειράς που θα ελεγχθεί |
| val | const char16_t * | Ο πίνακας χαρακτήρων που θα ελεγχθεί στην αρχή |

### Τιμή επιστροφής

true εάν το span ξεκινά με τον πίνακα χαρακτήρων, false διαφορετικά

## Δείτε επίσης

* Απαρίθμηση [StringComparison](../../system/stringcomparison/)
* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Κλάση [String](../../system/string/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)