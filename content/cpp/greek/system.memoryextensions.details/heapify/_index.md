---
title: Heapify()
second_title: Aspose.Slides για C++ API Αναφορά
description: Διατηρεί την ιδιότητα του σωρού για ζεύγη κλειδιού-τιμής.
type: docs
weight: 92
url: /el/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) συνάρτηση


Διατηρεί την ιδιότητα του σωρού για ζεύγη κλειδιού-τιμής.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Ο τύπος των κλειδιών |
| TValue | Ο τύπος των τιμών |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Η περιοχή των κλειδιών στο σωρό |
| values | [Span](../../system/span/)\<TValue\>\& | Η περιοχή των τιμών στο σωρό |
| n | **int32_t** | Μέγεθος του σωρού |
| i | **int32_t** | Δείκτης για heapify |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) συνάρτηση για κλειδιά |

## Δείτε επίσης

* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)