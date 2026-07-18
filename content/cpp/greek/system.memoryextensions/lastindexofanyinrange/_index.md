---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides για C++ API Αναφορά
description: Βρίσκει την τελευταία εμφάνιση οποιουδήποτε στοιχείου εντός του καθορισμένου εύρους μέσα σε ένα span.
type: docs
weight: 261
url: /el/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) συνάρτηση


Βρίσκει την τελευταία εμφάνιση οποιουδήποτε στοιχείου εντός του καθορισμένου εύρους σε ένα span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span μέσα στο οποίο θα γίνει η αναζήτηση |
| lowInclusive | const T\& | Το κατώτερο όριο του εύρους (συμπεριλαμβανομένου) |
| highInclusive | const T\& | Το ανώτερο όριο του εύρους (συμπεριλαμβανομένου) |

### Τιμή επιστροφής

Ο δείκτης μηδενικής βάσης του τελευταίου στοιχείου εντός του εύρους, ή -1 εάν δεν βρεθεί

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) συνάρτηση


Βρίσκει την τελευταία εμφάνιση οποιουδήποτε στοιχείου εντός του καθορισμένου εύρους σε ένα μεταβλητό span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span μέσα στο οποίο θα γίνει η αναζήτηση |
| lowInclusive | const T\& | Το κατώτερο όριο του εύρους (συμπεριλαμβανομένου) |
| highInclusive | const T\& | Το ανώτερο όριο του εύρους (συμπεριλαμβανομένου) |

### Τιμή επιστροφής

Ο δείκτης μηδενικής βάσης του τελευταίου στοιχείου εντός του εύρους, ή -1 εάν δεν βρεθεί

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)