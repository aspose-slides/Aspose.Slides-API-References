---
title: ContainsAnyExcept()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Ελέγχει εάν ένα read-only span περιέχει οποιοδήποτε στοιχείο εκτός από τρεις καθορισμένες τιμές.
type: docs
weight: 66
url: /el/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) συνάρτηση

Ελέγχει εάν ένα read-only span περιέχει οποιοδήποτε στοιχείο εκτός από τρεις καθορισμένες τιμές.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span για αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή για εξαίρεση |
| value1 | const T\& | Η δεύτερη τιμή για εξαίρεση |
| value2 | const T\& | Η τρίτη τιμή για εξαίρεση |

### Τιμή επιστροφής

true εάν βρεθεί οποιοδήποτε στοιχείο διαφορετικό από τις καθορισμένες τιμές, false διαφορετικά

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) συνάρτηση

Ελέγχει εάν ένα mutable span περιέχει οποιοδήποτε στοιχείο εκτός από τρεις καθορισμένες τιμές.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το mutable span για αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή για εξαίρεση |
| value1 | const T\& | Η δεύτερη τιμή για εξαίρεση |
| value2 | const T\& | Η τρίτη τιμή για εξαίρεση |

### Τιμή επιστροφής

true εάν βρεθεί οποιοδήποτε στοιχείο διαφορετικό από τις καθορισμένες τιμές, false διαφορετικά

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) συνάρτηση

Ελέγχει εάν ένα read-only span περιέχει οποιοδήποτε στοιχείο εκτός από δύο καθορισμένες τιμές.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span για αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή για εξαίρεση |
| value1 | const T\& | Η δεύτερη τιμή για εξαίρεση |

### Τιμή επιστροφής

true εάν βρεθεί οποιοδήποτε στοιχείο διαφορετικό από τις καθορισμένες τιμές, false διαφορετικά

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) συνάρτηση

Ελέγχει εάν ένα mutable span περιέχει οποιοδήποτε στοιχείο εκτός από δύο καθορισμένες τιμές.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το mutable span για αναζήτηση |
| value0 | const T\& | Η πρώτη τιμή για εξαίρεση |
| value1 | const T\& | Η δεύτερη τιμή για εξαίρεση |

### Τιμή επιστροφής

true εάν βρεθεί οποιοδήποτε στοιχείο διαφορετικό από τις καθορισμένες τιμές, false διαφορετικά

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) συνάρτηση

Ελέγχει εάν ένα read-only span περιέχει οποιοδήποτε στοιχείο εκτός από μια καθορισμένη τιμή.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span για αναζήτηση |
| value | const T\& | Η τιμή για εξαίρεση |

### Τιμή επιστροφής

true εάν βρεθεί οποιοδήποτε στοιχείο διαφορετικό από την καθορισμένη τιμή, false διαφορετικά

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) συνάρτηση

Ελέγχει εάν ένα mutable span περιέχει οποιοδήποτε στοιχείο εκτός από μια καθορισμένη τιμή.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το mutable span για αναζήτηση |
| value | const T\& | Η τιμή για εξαίρεση |

### Τιμή επιστροφής

true εάν βρεθεί οποιοδήποτε στοιχείο διαφορετικό από την καθορισμένη τιμή, false διαφορετικά

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Ελέγχει εάν ένα read-only span περιέχει οποιοδήποτε στοιχείο εκτός από αυτά που βρίσκονται σε άλλο span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span για αναζήτηση |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span των τιμών προς εξαίρεση |

### Τιμή επιστροφής

true εάν βρεθεί οποιοδήποτε στοιχείο που δεν βρίσκεται στις τιμές, false διαφορετικά

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Ελέγχει εάν ένα mutable span περιέχει οποιοδήποτε στοιχείο εκτός από αυτά που βρίσκονται σε read-only span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το mutable span για αναζήτηση |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το read-only span των τιμών προς εξαίρεση |

### Τιμή επιστροφής

true εάν βρεθεί οποιοδήποτε στοιχείο που δεν βρίσκεται στις τιμές, false διαφορετικά

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)