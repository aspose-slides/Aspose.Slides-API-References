---
title: ContainsAny()
second_title: Αναφορά API του Aspose.Slides για C++
description: Ελέγχει εάν ένα span μόνο για ανάγνωση περιέχει κάποια από δύο τιμές.
type: docs
weight: 53
url: /el/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Ελέγχει εάν ένα span μόνο για ανάγνωση περιέχει κάποια από δύο τιμές.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span για αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή προς αναζήτηση |
| value1 | const T\& | Η δεύτερη τιμή προς αναζήτηση |

### Τιμή Επιστροφής

true αν κάποια από τις τιμές βρεθεί στο span, false διαφορετικά

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Ελέγχει εάν ένα span μόνο για ανάγνωση περιέχει κάποια από τρεις τιμές.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span για αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή προς αναζήτηση |
| value1 | const T\& | Η δεύτερη τιμή προς αναζήτηση |
| value2 | const T\& | Η τρίτη τιμή προς αναζήτηση |

### Τιμή Επιστροφής

true αν κάποια από τις τιμές βρεθεί στο span, false διαφορετικά

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) function

Ελέγχει εάν ένα μεταβλητό span περιέχει κάποια από δύο τιμές.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το μεταβλητό span για αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή προς αναζήτηση |
| value1 | const T\& | Η δεύτερη τιμή προς αναζήτηση |

### Τιμή Επιστροφής

true αν κάποια από τις τιμές βρεθεί στο span, false διαφορετικά

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Ελέγχει εάν ένα μεταβλητό span περιέχει κάποια από τρεις τιμές.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το μεταβλητό span για αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή προς αναζήτηση |
| value1 | const T\& | Η δεύτερη τιμή προς αναζήτηση |
| value2 | const T\& | Η τρίτη τιμή προς αναζήτηση |

### Τιμή Επιστροφής

true αν κάποια από τις τιμές βρεθεί στο span, false διαφορετικά

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Ελέγχει εάν ένα span μόνο για ανάγνωση περιέχει κάποια τιμή από άλλο span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span για αναζήτηση |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span των τιμών προς αναζήτηση |

### Τιμή Επιστροφής

true αν κάποια τιμή από values βρεθεί στο span, false διαφορετικά

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Ελέγχει εάν ένα μεταβλητό span περιέχει κάποια τιμή από span μόνο για ανάγνωση.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το μεταβλητό span για αναζήτηση |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span μόνο για ανάγνωση των τιμών προς αναζήτηση |

### Τιμή Επιστροφής

true αν κάποια τιμή από values βρεθεί στο span, false διαφορετικά

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)