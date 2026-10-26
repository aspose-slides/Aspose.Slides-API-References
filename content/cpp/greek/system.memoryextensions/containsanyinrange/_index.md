---
title: ContainsAnyInRange()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ελέγχει εάν ένα span μόνο για ανάγνωση περιέχει οποιοδήποτε στοιχείο εντός του καθορισμένου εύρους.
type: docs
weight: 92
url: /el/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Ελέγχει εάν ένα span μόνο για ανάγνωση περιέχει οποιοδήποτε στοιχείο εντός του καθορισμένου εύρους.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span (πρέπει να είναι συγκρίσιμος) |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span για αναζήτηση |
| lowInclusive | const T\& | Το κατώτερο όριο (συμπεριλαμβανομένο) |
| highInclusive | const T\& | Το ανώτερο όριο (συμπεριλαμβανομένο) |

### Τιμή επιστροφής

αληθές εάν βρεθεί οποιοδήποτε στοιχείο εντός του εύρους, ψευδές διαφορετικά

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

Ελέγχει εάν ένα span με δυνατότητα τροποποίησης περιέχει οποιοδήποτε στοιχείο εντός του καθορισμένου εύρους.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span (πρέπει να είναι συγκρίσιμος) |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το μεταβλητό span για αναζήτηση |
| lowInclusive | const T\& | Το κατώτερο όριο (συμπεριλαμβανομένο) |
| highInclusive | const T\& | Το ανώτερο όριο (συμπεριλαμβανομένο) |

### Τιμή επιστροφής

αληθές εάν βρεθεί οποιοδήποτε στοιχείο εντός του εύρους, ψευδές διαφορετικά

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)