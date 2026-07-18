---
title: LastIndexOfImpl()
second_title: Αναφορά API Aspose.Slides για C++
description: Εντοπίζει τον τελευταίο δείκτη μιας τιμής σε ένα span.
type: docs
weight: 14
url: /el/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) συνάρτηση

Εντοπίζει τον τελευταίο δείκτη μιας τιμής σε ένα span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος των στοιχείων στο span |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) για αναζήτηση |
| length | **int32_t** | Μήκος για αναζήτηση |
| value | const T\& | Τιμή για εύρεση |

### Τιμή επιστροφής

Τελευταίος δείκτης της τιμής, ή -1 αν δεν βρεθεί

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Χώρος ονομάτων [System::MemoryExtensions::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)