---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ελέγχει αν ένα read-only span περιέχει οποιοδήποτε στοιχείο εκτός του καθορισμένου εύρους.
type: docs
weight: 79
url: /el/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) συνάρτηση

Ελέγχει αν ένα read-only span περιέχει οποιοδήποτε στοιχείο εκτός του καθορισμένου εύρους.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
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

true εάν βρεθεί κάποιο στοιχείο εκτός του εύρους, false διαφορετικά

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) συνάρτηση

Ελέγχει αν ένα mutable span περιέχει οποιοδήποτε στοιχείο εκτός του καθορισμένου εύρους.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span (πρέπει να είναι συγκρίσιμος) |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το mutable span για αναζήτηση |
| lowInclusive | const T\& | Το κατώτερο όριο (συμπεριλαμβανομένο) |
| highInclusive | const T\& | Το ανώτερο όριο (συμπεριλαμβανομένο) |

### Τιμή επιστροφής

true εάν βρεθεί κάποιο στοιχείο εκτός του εύρους, false διαφορετικά

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)