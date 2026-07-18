---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides για C++ Αναφορά API
description: Βρίσκει την τελευταία εμφάνιση οποιουδήποτε στοιχείου εκτός του καθορισμένου εύρους σε μια περιοχή.
type: docs
weight: 248
url: /el/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Βρίσκει την τελευταία εμφάνιση οποιουδήποτε στοιχείου εκτός του καθορισμένου εύρους εντός μιας περιοχής.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στην περιοχή |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Η περιοχή στην οποία γίνεται η αναζήτηση |
| lowInclusive | const T\& | Το κατώτερο όριο του εύρους (συμπεριλαμβανομένο) |
| highInclusive | const T\& | Το ανώτερο όριο του εύρους (συμπεριλαμβανομένο) |

### Τιμή Επιστροφής

Ο δεικτης μηδενικής βάσης του τελευταίου στοιχείου εκτός του εύρους, ή -1 αν δεν βρεθεί

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function

Βρίσκει την τελευταία εμφάνιση οποιουδήποτε στοιχείου εκτός του καθορισμένου εύρους εντός μιας μεταβλητής περιοχής.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στην περιοχή |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Η περιοχή στην οποία γίνεται η αναζήτηση |
| lowInclusive | const T\& | Το κατώτερο όριο του εύρους (συμπεριλαμβανομένο) |
| highInclusive | const T\& | Το ανώτερο όριο του εύρους (συμπεριλαμβανομένο) |

### Τιμή Επιστροφής

Ο δεικτης μηδενικής βάσης του τελευταίου στοιχείου εκτός του εύρους, ή -1 αν δεν βρεθεί

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)