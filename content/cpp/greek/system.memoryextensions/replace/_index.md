---
title: Replace()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντικαθιστά όλες τις εμφανίσεις μιας τιμής με μια νέα τιμή σε ένα Span.
type: docs
weight: 287
url: /el/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) συνάρτηση


Αντικαθιστά όλες τις εμφανίσεις μιας τιμής με μια νέα τιμή σε ένα [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Το span για τροποποίηση εντός μνήμης |
| oldValue | const T\& | Η τιμή προς αναζήτηση και αντικατάσταση |
| newValue | const T\& | Η νέα τιμή με την οποία αντικαθίσταται η oldValue |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) συνάρτηση


Αντιγράφει στοιχεία από την πηγή στον προορισμό, αντικαθιστώντας καθορισμένες τιμές κατά την αντιγραφή.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το πηγαίο [ReadOnlySpan](../../system/readonlyspan/) από το οποίο γίνεται η αντιγραφή |
| destination | [Span](../../system/span/)\<T\>\& | Ο προορισμός [Span](../../system/span/) προς τον οποίο γίνεται η αντιγραφή |
| oldValue | const T\& | Η τιμή προς αναζήτηση και αντικατάσταση κατά την αντιγραφή |
| newValue | const T\& | Η νέα τιμή με την οποία αντικαθίσταται η oldValue |

## Δείτε επίσης

* Κλάση [Span](../../system/span/)
* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)