---
title: CommonPrefixLength()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εντοπίζει το μήκος του κοινού προθέματος μεταξύ δύο διαστημάτων.
type: docs
weight: 27
url: /el/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Εντοπίζει το μήκος του κοινού προθέματος μεταξύ δύο διαστημάτων.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα διαστήματα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το πρώτο διάστημα |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το δεύτερο διάστημα |

### Τιμή επιστροφής

Ο αριθμός των ταιριαστών στοιχείων στην αρχή και των δύο διαστημάτων

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Εντοπίζει το μήκος του κοινού προθέματος μεταξύ ενός μεταβλητού διαστήματος και ενός διαστήματος μόνο για ανάγνωση.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα διαστήματα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το μεταβλητό διάστημα |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το διάστημα μόνο για ανάγνωση |

### Τιμή επιστροφής

Ο αριθμός των ταιριαστών στοιχείων στην αρχή και των δύο διαστημάτων

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) function

Εντοπίζει το μήκος του κοινού προθέματος μεταξύ δύο μεταβλητών διαστημάτων.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα διαστήματα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το πρώτο μεταβλητό διάστημα |
| other | const [Span](../../system/span/)\<T\>\& | Το δεύτερο μεταβλητό διάστημα |

### Τιμή επιστροφής

Ο αριθμός των ταιριαστών στοιχείων στην αρχή και των δύο διαστημάτων

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

Εντοπίζει το μήκος του κοινού προθέματος μεταξύ δύο διαστημάτων χρησιμοποιώντας έναν προσαρμοσμένο συγκριτή ισότητας.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα διαστήματα |
| TEqualityComparer | Ο τύπος του συγκριτή ισότητας |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το πρώτο διάστημα |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το δεύτερο διάστημα |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Ο συγκριτής ισότητας που θα χρησιμοποιηθεί για τη σύγκριση των στοιχείων |

### Τιμή επιστροφής

Ο αριθμός των ταιριαστών στοιχείων στην αρχή και των δύο διαστημάτων

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

Εντοπίζει το μήκος του κοινού προθέματος μεταξύ ενός μεταβλητού διαστήματος και ενός διαστήματος μόνο για ανάγνωση χρησιμοποιώντας έναν προσαρμοσμένο συγκριτή ισότητας.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα διαστήματα |
| TEqualityComparer | Ο τύπος του συγκριτή ισότητας |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το μεταβλητό διάστημα |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το διάστημα μόνο για ανάγνωση |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Ο συγκριτής ισότητας που θα χρησιμοποιηθεί για τη σύγκριση των στοιχείων |

### Τιμή επιστροφής

Ο αριθμός των ταιριαστών στοιχείων στην αρχή και των δύο διαστημάτων

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

Εντοπίζει το μήκος του κοινού προθέματος μεταξύ δύο μεταβλητών διαστημάτων χρησιμοποιώντας έναν προσαρμοσμένο συγκριτή ισότητας.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα διαστήματα |
| TEqualityComparer | Ο τύπος του συγκριτή ισότητας |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το πρώτο μεταβλητό διάστημα |
| other | const [Span](../../system/span/)\<T\>\& | Το δεύτερο μεταβλητό διάστημα |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Ο συγκριτής ισότητας που θα χρησιμοποιηθεί για τη σύγκριση των στοιχείων |

### Τιμή επιστροφής

Ο αριθμός των ταιριαστών στοιχείων στην αρχή και των δύο διαστημάτων

## Δείτε επίσης

* Typedef [SharedPtr](../../system/sharedptr/)
* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)