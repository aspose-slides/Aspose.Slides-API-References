---
title: HeapSort()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Εκτελεί ταξινόμηση heap σε ζεύγη κλειδιού-τιμής.
type: docs
weight: 79
url: /el/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) συνάρτηση

Εκτελεί ταξινόμηση heap σε ζεύγη κλειδιού-τιμής.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Ο τύπος των κλειδιών |
| TValue | Ο τύπος των τιμών |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Η περιοχή (span) των κλειδιών για ταξινόμηση |
| values | [Span](../../system/span/)\<TValue\>\& | Η περιοχή (span) των τιμών για ταξινόμηση |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) συνάρτηση για κλειδιά |

## Δείτε επίσης

* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)