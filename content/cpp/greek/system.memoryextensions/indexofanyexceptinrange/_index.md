---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides για την τεκμηρίωση API του C++
description: Βρίσκει τον δείκτη του πρώτου στοιχείου που βρίσκεται εκτός του καθορισμένου εύρους σε ένα ReadOnlySpan<T>
type: docs
weight: 183
url: /el/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) συνάρτηση


Βρίσκει το δείκτη του πρώτου στοιχείου που βρίσκεται εκτός του καθορισμένου εύρους σε ένα ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span στο οποίο γίνεται η αναζήτηση |
| lowInclusive | const T\& | Το κατώτερο όριο του εύρους (συμπεριλαμβανομένου) |
| highInclusive | const T\& | Το ανώτερο όριο του εύρους (συμπεριλαμβανομένου) |

### Τιμή Επιστροφής

Ο δείκτης με βάση το μηδέν του πρώτου στοιχείου εκτός του εύρους, ή -1 εάν δεν βρεθεί

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) συνάρτηση


Βρίσκει το δείκτη του πρώτου στοιχείου που βρίσκεται εκτός του καθορισμένου εύρους σε ένα Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το span στο οποίο γίνεται η αναζήτηση |
| lowInclusive | const T\& | Το κατώτερο όριο του εύρους (συμπεριλαμβανομένου) |
| highInclusive | const T\& | Το ανώτερο όριο του εύρους (συμπεριλαμβανομένου) |

### Τιμή Επιστροφής

Ο δείκτης με βάση το μηδέν του πρώτου στοιχείου εκτός του εύρους, ή -1 εάν δεν βρεθεί

## Δείτε επίσης

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)