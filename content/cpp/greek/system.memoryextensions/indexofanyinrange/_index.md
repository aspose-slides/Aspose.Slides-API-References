---
title: IndexOfAnyInRange()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Βρίσκει το δείκτη του πρώτου στοιχείου που βρίσκεται εντός του καθορισμένου εύρους σε ένα ReadOnlySpan<T>
type: docs
weight: 196
url: /el/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) συνάρτηση

Εντοπίζει το δείκτη του πρώτου στοιχείου που βρίσκεται εντός του καθορισμένου εύρους σε ένα ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span για αναζήτηση |
| lowInclusive | const T\& | Το κατώτερο όριο του εύρους (συμπεριλαμβανομένου) |
| highInclusive | const T\& | Το ανώτερο όριο του εύρους (συμπεριλαμβανομένου) |

### Τιμή επιστροφής

Ο μηδενική-βάση δείκτης του πρώτου στοιχείου εντός του εύρους, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) συνάρτηση

Εντοπίζει το δείκτη του πρώτου στοιχείου που βρίσκεται εντός του καθορισμένου εύρους σε ένα Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span για αναζήτηση |
| lowInclusive | const T\& | Το κατώτερο όριο του εύρους (συμπεριλαμβανομένου) |
| highInclusive | const T\& | Το ανώτερο όριο του εύρους (συμπεριλαμβανομένου) |

### Τιμή επιστροφής

Ο μηδενική-βάση δείκτης του πρώτου στοιχείου εντός του εύρους, ή -1 αν δεν βρεθεί

## Δείτε επίσης

* Τάξη [ReadOnlySpan](../../system/readonlyspan/)
* Τάξη [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)